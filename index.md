---
layout: default
---
### Anotace

Tento předmět nejprve seznámí studenty s algoritmickým stylem myšlení pomocí vytvoření programu ve vizuálním jazyce Scratch. Hlavní náplní předmětu bude úvod do programování v Pythonu. Studenti se seznámí s datovými typy, a naučí se psát funkce, cykly a podmínky v Pythonu. Částí kurzu bude také pochopení a tvorba výjimek a jejích důležitost v programování. Studenti se naučí sdílet svoji práci pomocí IPython notebooku a analyzovat data pomocí pandas s následnou vizulazací. Během celého předmětu budou studenti pracovat s verzovacím systémem Git, pomocí kterého budou ukládat výsledky své práce.

Kurz nevyžaduje předchozí znalost programování. V kurzu budou použity biologické příklady, které pomůžou studentům lépe pochopit strukturu jazyka Python a snadněji začít s programováním. Kurz bude ukončen zápočtem. Pro úspěšné absolvování kurzu je potřeba, aby studenti udělali projekt zpracování biologických dat, na němž budou pracovat během celého kurzu. Důraz bude kladen na naučení se algoritmického myšlení, což je obvykle nejproblematičtější oblast u studentů neinformatických oborů. 

Python je velmi přivětivý a dobře čitelný jazyk, který má velkou a nestále rostoucí komunitu uživatelů také z řad biologů.

### Cíl předmětu

Cílem předmětu je zbavení studentů strachu z programování a naučit je nejen příkazy pro zpracování dat, ale i způsoby, jak lze na problém podívat z pohledu algoritmického myšlení. Po úspěšném absolvování předmětu budou studenti schopni provádět analýzu dat jakýchkoliv dat v textovém formátu efektivněji a reproducibilně. Tento kurz může také poslouží studentům dobrým základem pro následné samostudium dalších nástrojů pro zpracování dat. Tento předmět je určen pro studenty, kteří nemají žádné základy programování, ale chtějí se naučit efektivní práci s daty.

### Kdy a kde

Každé úterý 17:20 - 18:50, učebna B311, Viničná 7, 3. patro.


### Sylabus
1. Algoritmické myšlení. <a href="https://docs.google.com/presentation/d/1g6h96oaRYAz2dwzjZ3-5WpYRRNZJM5jb77kmUXGKpfI/edit?usp=sharing" class="presentation">Přednáška</a>
1. Základy práce s příkazovým řádkem. <a href="https://docs.google.com/presentation/d/1e9TOV2jNVBGy46PbICdMy1zaBFO_t7EioO-_5hMPsIA/edit?usp=sharing" class="presentation">Přednáška</a>
1. Tvorba programu v jazyce [Scratch](https://scratch.mit.edu/). <a href="https://docs.google.com/presentation/d/1TgJmOyh2PVyplmLBBqDdtGdVHIAVERW0Fc4NCS0DXHU/edit?usp=sharing" class="presentation">Přednáška</a>
1. Verzovací systém Git. <a href="https://docs.google.com/presentation/d/1K1UCmaqndPBE1JLNYhMXLCSrQ6BlvZXPRXOhnnaXJiA/edit?usp=sharing" class="presentation">Přednáška</a>
1. Úvod do programování v Pythonu. Datové typy.
1. Datové typy - pokračování. 
1. Podmínky a cykly.
1. Funkce.
1. Práce s textovými soubory. [Pandas](http://pandas.pydata.org/). 
1. Vizualizace dat
1. Třídy a vyjímky
1. Import vlastních modulů. Spouštění Pythonu z příkazového řádku.

[Seznam splněných domácích úkolů](https://docs.google.com/spreadsheets/d/1VbooFGuj2_wCxS7EbUE3lnpNgIiTvneexpI2EKxN7hA/edit?usp=sharing)

Řešení ke cvičením 

### Užitečné odkazy

Markdown pro hezčí IPython Notebook. <a href="https://github.com/anastazie/python_biol_2016/blob/master/Python_markdown.ipynb" class="jupyter"> IPython notebook </a>

[Návod](https://docs.google.com/document/d/1fgUFZ8hWeT7fUlPuZywD2y6zjIXFiAc0hyWk91Aoj9I/edit?usp=sharing) na vložení IPython Notebooku na GitHub.

### Instalace

Pro kurz můžete používat Python 3.5 nebo 3.6, ale pozor, ne Python 2.

#### Windows

1. Nainstalujte Anacondu3 4.4.0. [32-bitovou](https://repo.continuum.io/archive/Anaconda3-4.4.0-Windows-x86.exe) nebo [64-bitovou](https://repo.continuum.io/archive/Anaconda3-4.4.0-Windows-x86_64.exe) dle typu vašého počítače. **Důležité: neinstalujte Anacondu3 5 - problémy s Git Bash!** 

Pandas už by měl být nainstalovaný. 

Pokud ne, nainstalujte ho pomocí příkazu `conda install pandas` např. v `GitBash`.


#### Linux, MacOS

Instalace Pythonu 3 v Ubuntu:

`sudo apt install python3 python3-pip`

Instalace Pythonu 3 v MacOS:

`brew install python3`
Pozn. pokud nemáte brew, nainstalujte jej podle [návodu na brew.sh](https://brew.sh).

Jakmile máte Python 3, můžete instalovat dále.

1. Nainstalujte pandas
`pip3 install pandas`

2. Nainstalujte Jupyter Notebook
`pip3 install jupyter`

### Spuštění Jupyter Notebooku

#### Windows

Protože máte python nainstalovaný pomocí Anacondy, program na spuštění Jupyter notebooku by měl byt v podsložce Anaconda.

#### Linux, MacOS

Spustíte Jupyter Notebook pomocí příkazu `jupyter notebook`

### Doporučená literatura

[Software Carpentry: The UNIX Shell](http://swcarpentry.github.io/shell-novice/)

[Data Carpentry](http://www.datacarpentry.org/lessons/)

[Practical computing for biologists](http://practicalcomputing.org/)

[Python for Biologists](http://pythonforbiologists.com)

[Python course in bioinformatics](http://users.ugent.be/~vstorme/files/PYTHON/PythonBioinformatics.pdf)

[Illustrating Python via Bioinformatics Examples](http://hplgit.github.io/bioinf-py/doc/pub/html/main_bioinf.html#)

[Introduction to Programming using Python](https://drive.google.com/file/d/0B99fAy7pKkctWm9obFk2WDc2NVU/view?usp=sharing)

[comment]: # (<a href="https://docs.google.com/presentation/d/1tFO22uSMCtcFkznsGPmpgUkQLuqHy6r90q_xSM0KNBs/edit?usp=sharing" class="presentation">Přednáška</a>)


[comment]: # (<a href="https://github.com/anastazie/python_biol_2016/blob/master/10_Python_Pandas.ipynb" class="jupyter"> IPython notebook </a>)
