# DPO-2017-18-AC3

REQUISITS: 

1. Resoldrel’exerciciambl’entorndeprogramacióIntelliJ.

2. Dipositar un ZIP al pou corresponent de l’eStudy amb data límit 26 de novembre de 2017. Caldrà generar un zip seguint el següent format AC3_login.zip, a partir de una carpeta que hadecontenir:
carpeta-de-la-que-faras-un-zip (Projecte IntelliJ) src Main.java (...) (Els altres .java que tingueu) (...) (Llibreries, dades i altres fitxers IntelliJ) Així doncs, la carpeta a comprimir contindrà els continguts del projecte de IntelliJ, carpeta del projecte generat. El qual ha de contenir una carpeta src que contingui un ﬁtxer Main.java ambelmètode main itotselsaltresﬁtxers .java quesiguinnecessaris.

3. El codi ha d’estar degudament comentat, ha de ser llegible (ben tabulat, variables amb nomsauto-explicatives...) iajustar-sealesJavaCodeConventions.

4. L’exercici és individual, si es detecta copia, llavors l’exercici serà qualiﬁcat amb una nota iguala0is’aplicaràlanormativadel’assignatura.


Des de la universitat, com no podria ser d’altra forma, ens preocupem per la pressió a la que es troben sotmesos els alumnes d’enginyeria. Són moltes les hores que s’han de dedicar a les diferents assignatures, fet que només es pot aconseguir mitjançant una escrupulosa planiﬁcació. Així, ens hem proposat desenvoluparunprogramaquesiguielnostremilloramicperencararelcursactualielsquevindran.
A falta d’obtenir tota la informació, que els serveis TIC prepararan més endavant, disposem d’un ﬁtxer enformat .json 
onhihaunasèried’alumnesiassignatures(superoﬁcials)perferlesprimeresproves.

Ensinteressapoderrealitzarlessegüentsfuncions:

• Veureelnombretotald’assignaturesobligatòriesaixícomeld’optatives.
• Calcularl’assignaturaambméssobrecàrregad’hores,ésadir,ambmésdiferènciapercentualentre les hores reals i les que es corresponen segons els crèdits (30 · n, on n és el nombre de crèdits) i mostrar-netotalainformació.
• Mostrarlainformaciópersonaldel’alumneambl’emailméscurtdelsistema.
Departamentd’Enginyeria-Informàtica 1
Curs2017-2018 DPOO-AC3
• Veure un llistat amb tota la informació personal dels professors que realitzen tasques de recerca a launiversitat.
• Veure un llistat dels noms dels 3 alumnes que més feina tenen aquest any, és a dir, que s’han matriculat a conjunts d’assignatures amb un total d’hores superior a la resta, així com la informació delesassignaturesquerealitzen.

Elprogramahauràde,inicialment,carregartotalainformaciódelﬁtxerJSONanomenat“laSallers.json”. Uncopfetaquestpas,esmostraràelsegüentmenú.

1. Consultar total d’assignatures obligatòries i optatives 
2. Consultar l’assignatura amb més sobrecàrrega d’hores 
3. Consultar alumne amb l’email més curt 
4. Consultar professors investigadors 
5. Consultar Top3 d’alumnes estressats 
6. Sortir
Sel·lecciona una opcio:

Snippet1: Menudesel·lecciódelprograma.

El menú serà la primera cosa que printi el programa, és a dir, el primer que sortirà per pantalla serà el número 1 delmenú. L’usuarihadepoderanarintroduïntopcions(mostrantcadacopelmateixmenúques’hamostratalarrencardesprésdemostrarlasortidadel’anterioropciósel·leccionada) ﬁns que decideixi sortir (opció 6). Cal controlar que el que l’usuari entra en el menú és correcte (podeu assumir ques’entraràunenter,peròheudecomprovarqueestiguialrangdevalorsdelmenú).

Calrespectarelformatdelmenú,ésadir,s’hademostrarexactamentelcontingutdelSnippet1;entre el 1 iels : .
Consideracions Perlarealitzaciódel’exercici,tingueuencompteelspuntssegüents:

1. PerimportarlallibreriaGSON,calseguirelspassosalaguiaGSONdisponibleal’eStudy.
2. PeraprendreallegirenJSON,usrecomanemferunamicadegoogling.
3. Es molt rellevant observar TOTS els valors les dades del ﬁtxer que tracteu i dimensionar correctament els atributs, especialment les hores reals, que han de poder emmagatzemarvalorsﬁns231.
