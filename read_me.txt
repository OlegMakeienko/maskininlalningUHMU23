Skapa ett problem:
jag har en service, vilken tar kommentarer och där kommer ganska många dåliga kommentarer så jag måste ta bort de dåliga.
Analisera data:
Jag har en data: en lista med kommentarer och måste kolla varje kommentar om den är bra eller dålig.
Kvalitet på datasets annotering:
Hur väl data är märkta eller annoterade.
Utveckla en binär klassificerare:
I mitt fall handlar problemet om att skilja mellan två möjliga utfall så en binär klassificerare är lämplig.
Välja en algoritm:
Jag ska välja två olika algoritmer som passar att lösa problemet: en av de blir slumpmässig skog och den andra - Logistic Regression
Träna modellen:
Jag låter modellen lära sig från mina data.
Testa modellen:
Mata modellen nya data för att se hur bra eller dålig blir resultatet.
Utvärdera modellen:
Jag ska använda precision och recall för att utvärdera modellens prestanda.


Precision och Recall är två viktiga prestandamått inom maskininlärning, särskilt för klassificeringsproblem.
Precision (även kallad positivt prediktivt värde) är andelen relevanta instanser bland de hämtade instanserna.
Det kvantifierar antalet positiva klassprognoser som faktiskt tillhör den positiva klassen.
Precision kan ses som ett mått på kvalitet.
Högre precision innebär att en algoritm returnerar fler relevanta resultat än irrelevanta.


Recall (även känd som känslighet) är andelen relevanta instanser som hämtades.
Det kvantifierar antalet positiva klassprognoser gjorda av alla positiva exempel i datauppsättningen.
Recall kan ses som ett mått på kvantitet.
Högt recall innebär att en algoritm returnerar de flesta av de relevanta resultaten.


Formellt kan dessa begrepp uttryckas med följande formler:
Precision =
 True Positives / (True Positives+False Positives)


Recall =
 True Positives / (True Positives+False Negatives)

Där:
True Positives (TP): Antalet korrekt identifierade positiva exempel.
False Positives (FP): Antalet negativa exempel felaktigt identifierade som positiva.
False Negatives (FN): Antalet positiva exempel felaktigt identifierade som negativa.

