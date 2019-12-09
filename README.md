OS kodutöö 3, kettapööruste planeerija
=======
Ehitatud kasutades `create-react-app`-i, kõige uuemat versiooni.

Kasutasin Reacti, Typescripti.

Käivitamiseks vaja mõnda uuemat `nodejs`-i (uusim LTS releasei), `npm`-i

Kui projektikaustas, jooksutage `npm install`. See installeerib vajalikud pakid.
Projekti püsti saamiseks jooksutage `npm start`. Kui see ei tööta, kasutage `npx react-scripts start`. Siis navigeerige http://localhost:3000-le, kust saate projekti vaadata.

Projekt on ka saadaval https://snemvalts.github.io/os_kodu3/

##Kui lisaks oleks vaja mõne protsessi kettapäringuid eelistada teiste protsesside päringutele, siis missugust planeerijat soovitaksite?

V: Sellisel juhul kasutaks FCFS/NOOP, andes kettale/kettaplaneerijale prioriteetses järjekorras pöördusmustri.
