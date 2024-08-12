<h1> Det her er forklaring på OSI modelen og TCP/IP Modelen </h1>

![net_models4 (1)](https://github.com/user-attachments/assets/19286397-bec1-4092-addd-94373ebcdf94)

<h2> OSI-modellen Open Systems Interconnection </h2>

<p>OSI-modellen er en konceptuel ramme udviklet af International Organization for Standardization (ISO), der beskriver, hvordan forskellige netværksprotokoller interagerer for at muliggøre kommunikation mellem computere på et netværk. Modellen opdeles i syv lag, hvor hvert lag har en specifik funktion i netværkskommunikationen: </p>

<h3> Lag 1: Fysisk lag (Physical Layer) </h3>

<p> Funktion: Ansvarlig for transmission af rå bitstrømme over et fysisk medium. Dette inkluderer hardware som kabler, switches og andet netværksudstyr. </p>

<p> Eksempler: Ethernet, USB. </p>

<h3>Lag 2: Datalink lag (Data Link Layer) </h3>

<p> Funktion: Sikrer, at data kan sendes til det korrekte fysiske medium ved hjælp af MAC-adresser. Det håndterer fejl i det fysiske lag. </p>

<p> Eksempler: Ethernet, Wi-Fi. </p>

<h3> Lag 3: Netværkslag (Network Layer) </h3>

<p> Funktion: Bestemmer, hvordan data pakkes, adresseres og dirigeres fra en node til en anden. IP-adresser anvendes på dette lag. </p>

<p> Eksempler: IP (Internet Protocol). </p>

<h3> Lag 4: Transportlag (Transport Layer) </h3>

<p> Funktion: Sikrer pålidelig dataoverførsel mellem to systemer. Dette lag håndterer flowkontrol, fejlretning og genforsendelse af tabte data. </p>

<p> Eksempler: TCP (Transmission Control Protocol), UDP (User Datagram Protocol) </p>

<h3> Lag 5: Session lag (Session Layer) </h3>

<p> Funktion: Styrer sessioner eller forbindelser mellem applikationer. Dette lag sørger for, at sessionen etableres, vedligeholdes og afsluttes korrekt. </p>

<p> Eksempler: NetBIOS, RPC (Remote Procedure Call). </p>

<h3> Lag 6: Præsentationslag (Presentation Layer) </h3>

<p> Funktion: Sørger for, at data præsenteres i en forståelig form. Det står for datatransformation, som kryptering, dekomprimering og datakonvertering. </p>

<p> Eksempler: SSL/TLS (for kryptering), JPEG, GIF (for billedformater) </p>

<h3> Lag 7: Applikationslag (Application Layer) </h3>

<p> Funktion: Giver netværksservices direkte til applikationerne. Dette lag håndterer brugergrænseflader og applikationskommunikation. </p>

<p> Eksempler: HTTP, FTP, SMTP. </p>
