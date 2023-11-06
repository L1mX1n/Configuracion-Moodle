# Configuracion-Moodle

## Configuració

**1.** Inicia sessió com a administrador del teu Moodle i realitza les següents tasques prèvies d'administració.

   **a)** Canvia la teva direcció de correu electrònic i també la teva contrasenya per una altra. Afegeix-te a més un avatar. Tot això es pot fer anant al teu perfil (opció que apareix sota el teu nom que es veu a la part superior dreta de la finestra del Moodle) i clicant sobre l'enllaç `Editar` (o també anant a l'opció `Preferències`, situada al mateix lloc).
   
   ![aa](/Fotos/Contrasenaycorreo.png)
   ![a](/Fotos/Fotodeperfil.png)

   **b)** Canvia el nom del teu lloc (tant llarg com curt) i fes que la pàgina principal no mostri res pels usuaris que no estiguin autentificats. Això es pot fer anant a l'opció `Administració del lloc > Primera plana > Paràmetres`
   
   ![aa](/Fotos/Paginaprincipal.png)

   **c)** Comprova que la franja horària del teu lloc sigui la correcta. Això es pot fer anant a l'opció `Administració del lloc > Ubicació > Paràmetres`.
   
   ![FotoHorario](/Fotos/ZonaHoraria.png)
   
   **d)** Canvia l'idioma del teu lloc. Això es pot fer anant a l'opció `Administració del lloc > Idioma > Paràmetres` i tenint en compte tant el checkbox `Detecció automàtica de l'idioma` com el desplegable `Idioma per defecte`.
   
   ![a](/Fotos/Idioma.png)
   ![a](/Fotos/Idioma2.png)
   
   **e)** Canvia la política de contrasenyes de manera que els usuaris que es creiïn tinguin una contrasenya de com a mínim 4 caràcters incloent-hi, majúscules, minúscules i xifres. Això es pot fer anant a l'opció `Administració del lloc > Seguretat >Normatives del lloc`.

![a](/Fotos/Contrasena4digitos.png)

**2.** Crea els següents cursos: un curs anomenat A (sense categoria) que estigui format per 3 temes i un altre anomenat B (també sense categoria) que estigui format per 5 temes. Tot això ho pots fer des de Administració del lloc->Gestiona cursos i categories o també des del quadre `Navegació` anant a `Cursos > Afegeix curs`

![a](/Fotos/CursoA.png)
![a](/Fotos/CursoB.png)

**3.** Vés a algun dels cursos creats al punt anterior (simplement seleccionant-lo dins del quadre `Navegació`) i fes que contingui en algun del seus temes algun tipus de material (un document PDF, per exemple), canvia el títol d'algun tema i, en general, investiga les possibilitats que et dóna el botó `Activar edició` en un curs.

![a](/Fotos/Tascapdf.png)

**4.** Creació d’usuaris i alumnes. 
   
   **a)** Crea manualment un usuari anomenat `Bob` que ha de fer servir el `mètode d'autenticació manual`. Això es pot fer des de `Administració del lloc > Usuaris > Comptes > Afegeix un usuari`

![a](/Fotos/Bob.png) 

   **b)** Genera deu alumnes que ho seran dels dos cursos A i B . Fes servir un arxiu CSV per realitzar aquesta creació en bloc. Vés a `Administració del lloc > Usuaris > Comptes > Carrega usuaris` i segueix els passos que et marca. 
   
![a](/Fotos/10alumnos.png)
   
   **c)** Elimina dos dels deu alumnes creats a l'apartat anterior fent servir l'opció `Administració del lloc > Usuaris > Accions amb usuaris en bloc`

![a](/Fotos/Eliminar2usuarios.png)

**5.** Ara matricula aquests usuaris als diferents cursos.
   **a)** Assigna com a professor del curs B l'usuari "Bob" i com a alumnes a tots els que fas afegir des de l'arxiu CSV Tot això ho pots fer anant a `Administració del curs > Usuaris inscrits > Inscriure`.

![a](/Fotos/Bobprofesor.png)

**6.** Canvia l'aparença estètica del teu lloc. Concretament, descarrega't i activa un tema diferent dels que venen per defecte i prova de canviar també la capçalera i el peu de pàgina del lloc. Això ho pots fer primer anant a `Administració del lloc > Connectors > Instal·lar complement` i després a `Administració del lloc > Aparença > Temes > Selector de temes` Sempre pots fer servir l'enllaç `Canvi de rol` del menú de la dreta per observar com es veuria el lloc sent alumne, professor, etc.

![a](/Fotos/Seleccionartema.png)

**7.** Assigna un professor i matricula alumnes al curs A.

![a](/Fotos/Bobprofesor.png)

**8.** Amb el professor afegeix contingut al curs A. Afegeix diferents tipus d’activitats i recursos. Crea una tasca amb data d’entrega oberta que demani la càrrega d’un fitxer PDF.

![a](/Fotos/Uf1Nf1nf2.png)

**9.** Entra amb un alumne i comprova que pots lliurar la tasca.

![a](/Fotos/Entregaalumnopdf.png)