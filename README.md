# ProjectTwitter
Ne propunem să recreem populara rețea de socializare Twitter. Un ochi atent va observa că orice rețea de socializare bazată pe postări text reprezintă fundația pentru alte rețele de socializare cu feature-uri mult mai complexe.
--------------------------------------------------------------------------------------------

    Funcționalitățile aplicației client sunt:
- La pornire, unui utilizator i se oferă posibilitatea de a se loga în contul său sau își poate crea un cont. Logarea/înregistrarea presupune introducerea numelui de utilizator.
- Atenție: numele de utilizator trebuie să fie unic!
- Meniul principal afișează următoarele opțiuni (funcționalități):
- Post: utilizatorul poate face o postare text de maxim 140 de caractere;
- Personal Profile: utilizatorul își poate vedea istoricul postărilor sale
- Funcție de follow: utilizator poate să se “împrietenească” cu alți utilizatori. În acest fel puteți construi graful social al platformei.
- Feed - vizualizarea de postări. Se va afișa câte o postare o dată - pentru detalii vedeți mai jos. Sub postare se vor afla următoarele opțiuni: 
- Like sau Dislike - utilizatorul poate da like/dislike și își poate retrage reacția
- Comment - utilizatorul poate scrie un comentariu, iar lista de comentarii va fi updatată
- Retweet - utilizatorul va putea introduce o prefață postării sale
- Go to referenced tweet - dacă postarea este un retweet, se va putea accesa postarea inițială
- Keyword Search: utilizatorul introduce un query format din mai multe cuvinte cheie și se afișează postări care conțin cel puțin un keyword căutat - vedeți Inverted Index.
- User Search: utilizatorul introduce un nume de utilizator drept query și i se afișează lista de rezultate. Un rezultat nu trebuie să fie neapărat identic cu query-ul, ci se pot afișa și valori apropiate. Pentru a compara stringuri implementați distanța Levenshtein.

----------------------------------------------------------------------------------------------
- Networking - comunicarea dintre aplicațiile de client și server să se realizeze folosind Sockets
- Baze de date - datele utilizate de către server vor fi manipulate folosind o bază de date
