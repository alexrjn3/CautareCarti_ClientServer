Fișiere:
•	Server.java – gestionează conexiunile multiple și trimite răspunsurile.
•	FirClient.java – rulează pe un fir separat pentru fiecare client conectat.
•	Client.java – interfața utilizatorului; trimite cereri către server.

Pasi:
•	Clientul trimite cererea (autor + titlu).
•	Serverul procesează cererea, caută cartea în fișier și returnează răspunsul.
•	Suport pentru mai mulți clienți simultan.
•	Comunicarea se face prin socket-uri TCP.

Aplicație networked, cu interacțiune în timp real între clienți și server.
