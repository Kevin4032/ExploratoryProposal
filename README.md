# ExploratoryProposal


## Aanpak

Mijn uitgangspunt is de data, niet de onderzoeksvraag. Bij het bekijken van de GDC zag ik dat 'drinkers' en 'smokers' een mogelijkheid was (de category 'exposure'). Dat vind ik een interessant uitgangspunt, niet voor alle 'diseases' is deze category.

Vanaf dat punt heb ik gekeken wat mij datasets opleverde van het liefst 100 of meer.
Dat was bij zowel rokers als drinkers 'adenomas and adenocarcinomas'.
adenomas = goedaardig
adenocarcinomas = kwaadaardig

De 'smokers' hebben sets van kidney en lung, met een redelijke verdeling mannen en vrouwen (118/83).
Ook de 'drinkers' hebben sets van kidney en lung, de verdeling mannen en vrouwen is 213/113.

Mijn beeld, mijn aanname, is ook dat als die categorien niet gespecificeerd zijn, dat die datasets óók gebruikt kunnen worden, als extra category 'onbekend roker/drinker' (toelichting over category volgt hieronder)

![drinkers](/image/dataSet_003_drinkers.png "drinkers")

De balans in de leeftijd van de sets kan zoeken zijn

![smokers](/image/dataSet_002.png "smokers")

## Data

Bij het bekijk van de data zie ik geen mogelijkheid tot het filteren tussen 'drinkers', 'smokers' of elk ander attribuut.
Omdat de docent in de klas liet zien het datatype 'RNA-Seq' heb ik dat ook aangehouden.
Daarvan zijn de velden;
gene_id	gene_name	gene_type	unstranded	stranded_first	stranded_second	tpm_unstranded	fpkm_unstranded	fpkm_uq_unstranded

Daarmee heb ik het beeld dat het relevant is hoe we de data selecteren, welke attributen, en zorgen dat we de data goed gescheiden houden.

Voor mijzelf heb ik bijvoorbeeld een GDC cohort met 'drinkers' en 'male', naast een 'drinkers' en 'female'.
Hoe ik het voor me zie is dat het in ons onderzoek in 1 set komt, maar, wij differentieren dat met kolommen in de dataset (one hot encoding per category (ie. roker, drinker, male, lung, etc))

De reden dat ik in de chat iets opmerkte over ras is omdat het een attribuut is, en ik denk dat het helpt als we zorgen dat data gebalanceerd is, of, dat we in ieder geval ons bewust zijn van wat we meenemen; zoals hierboven benoemd, dat we weten wat we selecteren.

![category](/image/dataSet_001.png "category")

## Mijn hulpvraag / waar ik het moeilijk vind worden

Wat ik lastig vind is een goede richting te kiezen met een scope.
Enerzijds 'Focus on adenomas and adenocarcinomas in a specific organ, such as the colon or pancreas, to identify unique risk factors or treatment approaches'
Anderzijds 'Lifestyle Factors and Progression: Investigate the role of smoking and alcohol consumption in the progression of adenomas to adenocarcinomas.'


## Poging tot onderzoeksvraag

Als ik hulp vraag van AI kom ik tot de volgende onderwerpen;
Longen:
Adenocarcinoma is the most common type of non-small cell lung cancer (NSCLC), accounting for approximately 40% of all lung cancers

Nieren:
Renal cell carcinoma (RCC) is the most common type of kidney cancer, and adenocarcinoma is a subtype of RCC

## Grootte van de data

De data uit het screenshot is ongeveer 700MB voor drinkers.



