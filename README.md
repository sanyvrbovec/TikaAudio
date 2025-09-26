Tika Audio v1.0
Tika Audio v1.0 je jednostavan, ali moćan audio editor koji radi izravno u vašem web pregledniku. Dizajniran je za preciznu manipulaciju zvuka na razini pojedinačnog sample-a, koristeći interno 32-bitno float procesiranje kako bi se osigurala maksimalna kvaliteta i izbjegli gubici prilikom obrade.
<img width="1302" height="674" alt="image" src="https://github.com/user-attachments/assets/7c4aad8f-6671-4af2-a27c-48a88b3bc529" />

Ovaj alat je napravljen kao jedna samostalna HTML datoteka, bez vanjskih ovisnosti, što ga čini izuzetno prenosivim i lakim za korištenje.

<!-- Ovdje možete staviti screenshot aplikacije -->

✨ Glavne Značajke
Lossless Obrada: Sva audio obrada se odvija u 32-bitnom float formatu, što omogućuje promjene glasnoće i normalizaciju bez ikakvih gubitaka u kvaliteti zvuka.

Uređivanje na Razini Sample-a: Zumirajte valni oblik do krajnjih granica i koristite "Olovka" alat za direktno crtanje ili pomicanje pojedinačnih sampleova.

Marker Sustav: Precizno ubacujte i uklanjajte markere (sample s vrijednošću -1.0) bez uništavanja audio podataka.

Normalizacija i Pojačanje: Inteligentna normalizacija na zadanu dB vrijednost i jednostavno pojačanje u postocima.

Undo/Redo Sustav: Pratite povijest svojih izmjena i jednostavno poništite ili ponovite svaku akciju.

Izvoz Visoke Kvalitete: Izvezite svoj rad u nekomprimirani 16-bitni ili 24-bitni WAV format.

Potpuno Responzivan: Koristite aplikaciju na desktopu, tabletu ili mobitelu. Sučelje je prilagođeno za rad na dodir.

Nema Instalacije: Sve što trebate je web preglednik. Učitajte audio datoteku s vašeg uređaja i počnite s radom.

🚀 Kako Koristiti
Učitaj Datoteku: Kliknite na gumb "📂 Učitaj fajl" i odaberite audio datoteku s vašeg računala ili mobitela (WAV, FLAC, MP3, itd.).

Navigacija:

Koristite Zoom klizač za približavanje ili udaljavanje.

Koristite Pan klizač (ili povucite mišem/prstom) za pomicanje po valnom obliku.

Uređivanje:

Odaberite alat "Olovka" i zumirajte dok ne vidite točkice (sampleove).

Kliknite i povucite točku da joj promijenite vrijednost.

Postavite playhead (vertikalnu liniju) na željeno mjesto i kliknite "➕" da ubacite marker.

Obrada:

Unesite postotak u polje "Pojačanje" da ručno pojačate signal.

Koristite "Normaliziraj na" za sigurno postizanje maksimalne glasnoće bez distorzije.

Izvoz:

Odaberite željeni format (16-bit ili 24-bit WAV).

Kliknite na "📥 Izvezi" kako biste preuzeli obrađenu datoteku. Markeri će automatski biti uklonjeni prilikom izvoza.

🛠️ Tehnički Detalji
Jezici: HTML, CSS, JavaScript (ES6)

API: Web Audio API za dekodiranje i reprodukciju zvuka.

Ovisnosti: Nema. Sve je sadržano u jednoj index.html datoteci.

Ovaj projekt je demo i služi kao primjer kako se moćne audio manipulacije mogu izvesti na klijentskoj strani koristeći moderne web tehnologije.
