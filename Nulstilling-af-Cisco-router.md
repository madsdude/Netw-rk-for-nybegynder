# Hurtig guide: Nulstilling af Cisco router eller switch til fabriksindstillinger

## 1. Tilslut konsol og log ind
- Tilslut via konsolkabel og åbn terminal (f.eks. PuTTY eller Tera Term).
- Log ind, hvis der er brugernavn/adgangskode.

## 2. Gå til privilegeret EXEC-mode
```bash
enable
```
Indtast evt. password.

3. Slet startkonfigurationen (startup-config)
```
write erase
```

```
erase startup-config
```
4. Slet VLAN-database (kun switches)
På switches skal du også slette VLAN-databasen for fuldstændig nulstilling:
```
delete vlan.dat
```
Bekræft ved prompt.

5. Genstart enheden
```
reload
```
Når den spørger, om du vil gemme konfigurationen, svar nej.

Eksempel på fuld session
```
enable
write erase
Erasing the nvram filesystem will remove all configuration files! Continue? [confirm]
delete vlan.dat  (kun switch)
Delete filename [vlan.dat]? [Tryk Enter]
reload
Proceed with reload? [confirm]
[Tryk Enter]
Enheden starter nu op med fabriksindstillinger.
```
