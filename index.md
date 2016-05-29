---
layout: default
---
### Anotace

Tento předmět nejprve seznámí studenty s algoritmickým stylem myšlení pomocí vytvoření programu ve vizuálním jazyce Scratch. Předmět bude rozdělen na dvě části: práce s příkazovou řádkou a úvod do  programování v Pythonu. Po seznámení s příkazovou řádkou si studenti vyzkouší zpracování textových souboru a pokročilejší vyhledávání v textu pomocí regulárních výrazů.  První část ukončí ukázka nástrojů pro příkazovou řádku, které se využívají pro zpracování genomických dat. 

Dále bude následovat úvod do programování v Pythonu. Studenti se seznámí s datovými typy, a naučí se psát funkce, cykly a podmínky v Pythonu. Částí kurzu bude také pochopení a tvorba výjimek a jejích důležitost v programování. Studenti se naučí sdílet svoji práci pomocí IPython notebooku a seznámí se s modulem Biopython.

Kurz nevyžaduje žádné předchozí znalosti práce s příkazovou řádkou a programování. V kurzu budou použity biologické příklady, které pomůžou studentům lépe pochopit strukturu jazyka Python a snadněji začít s programováním. Kurz bude ukončen zápočtem. Pro úspěšné absolvování kurzu je potřeba, aby studenti udělali projekt zpracování biologických dat, na němž budou pracovat během celého kurzu. Důraz bude kladen na naučení se algoritmického myšlení, což je obvykle nejproblematičtější oblast u studentů neinformatických oborů. 

Python je velmi přivětivý a dobře čitelný jazyk, který má velkou a nestále rostoucí komunitu uživatelů také z řád biologů.

### Cíl předmětu

Cílem předmětu je zbavení studentů strachu z příkazové řádky a naučit je nejen příkazy pro zpracování dat, ale i způsoby, jak lze na problém podívat z pohledu algoritmického myšlení. Po úspěšném absolvování předmětu budou studenti schopni provádět analýzu dat jakýchkoliv dat v textovém formátu efektivněji a reproducibilně. Tento kurz může také poslouží studentům dobrým základem pro následné samostudium dalších nástrojů pro zpracování dat. Tento předmět je určen pro studenty, kteří nemají žádné základy programování, ale chtějí se naučit efektivní práci s daty.

### Sylabus
1. Algoritmické myšlení. Tvorba programu v jazyce [Scratch](https://scratch.mit.edu/)
2. Seznámení s příkazovou řádkou. 
3. Práce s textem v příkazové řádce.
4. Regulární výrazy. Práce s textovým editorem.
5. Ukázka bioinformatických nástrojů pro příkazovou řádku (fastQC, bowtie2, samtools).
6. Úvod do programování v Pythonu.
7. Datové typy. 
8. Podmínky a cykly.
9. Funkce. Výjimky
10. Práce s textovými soubory. [Pandas](http://pandas.pydata.org/).
11. Sdílení práce, tvorba reportu datové analýzy. [Ipython notebook](http://jupyter.org/).
12. [Biopython](http://biopython.org/DIST/docs/tutorial/Tutorial.html)

### Doporučená literatura

[Practical computing for biologists](http://practicalcomputing.org/)

[Python for Biologists](http://pythonforbiologists.com)

[Python course in bioinformatics](http://users.ugent.be/~vstorme/files/PYTHON/PythonBioinformatics.pdf)

<ol>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ol>
