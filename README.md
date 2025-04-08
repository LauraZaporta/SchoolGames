# SchoolGames

Aquest repositori té dos dels meus projectes bàsics de videojocs desenvolupats amb Game Maker 2 utilitzant el seu propi llenguatge de programació; GML. Actualment no tinc accès al meu propi codi perquè vaig utilitzar una versió
no legítima del programa per desenvolupar ambdós projectes, no tenia usuari i vaig eliminar l'aplicació.

Documentació GML: https://manual.gamemaker.io/monthly/en/GameMaker_Language/GML_Reference/GML_Reference.htm

## Projectes
### *Trail Up*

**Idea de joc**

Trail Up és un minijoc simple que consisteix d’una carrera a contrarellotge d’habilitat i
de sort amb estètica pixelart.
El jugador controla a un personatge (Tails) que ha d’escalar al llarg d’un escenari
vertical i arribar a la meta abans que la música de fons s’acabi. Tails va ascendent a la
meta saltant en blocs generats proceduralment a cada partida i esquivant enemics
generats també de manera aleatòria.

**Mecàniques**

Les mecàniques en un videojoc són totes aquelles accions de l’usuari que poden
modificar l’estat del joc; és a dir la posició o les característiques concretes de qualsevol
objecte del programa.
Trail Up té poques mecàniques, però per aconseguir arribar al final del joc s’han d’anar
aprenent i integrant amb cada partida ja que la combinació de l’ús correcte de totes
elles resulta en la victòria del jugador.
Sabent això, les mecàniques són les següents:
- Moviment: És la més important de totes ja que permet a l’usuari controlar al
personatge amb les tecles W, A i D. Aquesta mecànica inclou moviment
horitzontal (córrer) i moviment vertical (saltar).
- Vores de la pantalla: Si el jugador es mou cap a una de les vores dreta o
esquerra de la pantalla aquest apareixerà per la vora contrària. És una
mecànica clau per esquivar enemics de manera efectiva (ja que els enemics
“reboten” a les vores, no les travessen) i a la vegada accedir saltant a blocs
que d’una altra manera no es podrien ni tocar.
- Object mystery: En una de cada tres partides es genera de manera aleatòria a
qualsevol lloc del mapa un objecte que té un símbol de pregunta. Si el jugador
el troba i decideix agafar-lo poden passar dues coses: o la seva potència de
salt augmenta (tenint el joc quasi guanyat si l’usuari es fixa bé en les seves
accions) o disminueix (fent que els salts per arribar als blocs més llunyans
hagin de ser més difícils i precisos).
- Timing i decisions: Més que una mecànica, és una característica del joc. Els
salts han de pensar-se abans de fer-se ja que, a part que els enemics estan en
constant moviment, a cada “fila” poden aparèixer d’un a dos blocs. Si només
apareix un el jugador no té opció, però si n’hi ha dos s’ha de raonar quin bloc
permet la via més curta cap al següent i a la vegada s’ha d’escollir un moment
precís (Timing) per evitar els enemics i ascendir el més ràpid possible. Tot això
s’ha de pensar constantment a cada salt, i es va dominant més a cada partida.

### *Let's eat a bit*

**Idea de joc**

Let's eat a bit és un altre minijoc simple que es basa la supervivència i l'obtenció de punts de 
manera simultània amb estètica pixelart. 
L'usuari juga mitjançant un personatge curiós (és una bola verda amb un barret i sí, el barret també
forma part de la hitbox de l'sprite) que ha d'evitar el menjar sa, que li treu vides, i ha de consumir
el menjar brossa, que li dóna punts. Guanya quan ha consumit el menjar equivalent a 200 punts.

**Mecàniques**

- Moviment: En aquest cas, el jugador es mou mitjançant les fletxetes en els eixos x i y de la mateixa 
manera (no hi ha gravetat, és un pla).
- Vores de la pantalla: Similarment a Trail Up, si el jugador es mou cap a una de les vores de la pantalla i la travessa aquest apareixerà per la vora contrària. És molt útil per esquivar i obtenir punts ràpidament.
- Devil mode: Si el jugador observa que quan li dóna a la tecla espai l'sprite del personatge canvia, és
curiós i ho fa tres vegades el joc canivarà a Devil mode, el que canvia la meta de 200 punts a 500.


M'agradaria afegir més característiques als dos projectes però ara no tinc el codi i en el seu moment no vaig poder.
