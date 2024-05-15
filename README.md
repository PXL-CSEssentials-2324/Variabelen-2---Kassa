# Variabelen 2: Kassa

Schrijf een toepassing waarbij het ondernemingsnummer van een bedrijf
wordt gecontroleerd én de prijs van een product wordt berekend.

Het controlecijfer van het ondernemingsnummer wordt via de opdrachtknop
*BtnControleCijfer* uitgerekend. Een ondernemingsnummer bestaat in
totaal uit 10 cijfers. De laatst twee cijfers controleren op de
juistheid. De opgave is om deze laatste cijfers te berekenen. De formule
hiervoor is het nummer delen door 97, de rest van deze deling wordt
gebruikt om van het getal 97 af te trekken. Dit resultaat vormt het
controlecijfer.

Vb.: Nummer 07071281 delen door 97. De rest van deze deling geeft het
getal 78. We trekken dit af van 97 en komen het cijfer 19 uit. Dit is
het controlecijfer voor dit ondernemingsnummer.

Rest van deling van 07071281 \\ 97 = 78

97 -- 78 = 19

Als gebruiker kan ik mijn ondernemingsnummer ingeven in het
corresponderende tekstvak, genaamd *TxtOndernemingsnummer*. Vervolgens
kan ik als gebruiker op de knop *BtnControleCijfer* klikken om het
controle nummer te berekenen. Het controle nummer verschijnt in het
tekstvak *TxtControleNummer*.

Als gebruiker kan ik een decimale prijs ingeven in het tekstvak
*TxtPrijs* en een aantal ingeven in het tekstvak *TxtAantal*. Vervolgens
kan ik als gebruiker op de knop *BtnBerekenen* klikken om de totaalprijs
te berekenen. De totaalprijs verschijnt in het tekstvak *TxtTeBetalen*.

Als gebruiker kan ik de inhoud van alle tekstvakken wissen door op de
knop *BtnWissen* te klikken.

Tot slot kan ik als gebruiker de applicatie afsluiten door op de
*BtnSluiten* knop te klikken.

![Afbeelding met tekst, schermopname, software, Computerpictogram
Automatisch gegenereerde
beschrijving](./media/image1.png)