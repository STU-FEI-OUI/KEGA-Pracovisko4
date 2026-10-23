# KEGA Projekt - Laboratórium aplikovaných technológií umelej inteligencie

## Zameranie projektu
Projekt sa zameriava na vybudovanie moderného laboratória aplikovaných technológií umelej
inteligencie pre priemysel. Laboratórium bude pozostávať z 5 rôznych pracovísk zameraných na
spracovanie obrazu, videa a zvuku pre priemyselné aplikácie. Pracoviská sú navrhnuté tak, aby mohli
byť nezávislé od operačného systému (Linux, Windows) a softvéru pre HNS (Matlab, Python, ...).
Laboratórium budú využívať študenti 3. ročníka bakalárskeho štúdia a študenti 1. a 2. ročníka
inžinierskeho štúdia na vybraných predmetoch a študenti bakalárskych, diplomových, individuálnych
a tímových prác, ale aj doktorandi. Plánujeme nasledovné pracoviská:

## Pracovisko 4 - Detekcia objektov na videu pomocou hlbokých neurónových sietí
Počítačová zostava, kvalitná kamera, Nvidia Jetson (Edge zariadenie), priemyselný riadiaci
systém. Cieľom pracoviska bude sledovanie pohybujúcich sa objektov na videu pomocou hlbokých
neurónových sietí.

### Rozpoznávanie ľudských činností na videu
**Rozpoznávanie ľudských činností na videu** (*Human Action Recognition*) predstavuje významnú oblasť počítačového videnia, ktorej cieľom je automatická identifikácia a klasifikácia činností vykonávaných človekom na základe analýzy videozáznamov. 
Na rozdiel od klasifikácie statických obrazov je pri rozpoznávaní činností potrebné zohľadniť nielen priestorové informácie o objektoch a ich okolí, ale aj časové zmeny a pohybové charakteristiky v jednotlivých snímkach videa. 
Na riešenie tejto úlohy sa využívajú metódy hlbokého učenia, najmä konvolučné neurónové siete (CNN), trojrozmerné konvolučné siete (3D CNN), rekurentné siete (LSTM) a vizuálne transformery.

**Cieľom úlohy** je navrhnúť a experimentálne overiť model hlbokého učenia na rozpoznávanie vybraných ľudských činností z videozáznamov. 
V rámci riešenia sa realizuje predspracovanie videí, extrakcia priestorových a časových príznakov, trénovanie modelu a vyhodnotenie úspešnosti klasifikácie. 
Na experimentálne overenie možno využiť verejne dostupné datasety, napríklad **UCF101 alebo HMDB51**, ktoré obsahujú videozáznamy rôznych ľudských činností.
Z dostupných metód sa budú používať CNN, CNN+SVM a CNN+LSTM modely.

( [Dataset_HMDB51](https://huggingface.co/datasets/Serrelab/hmdb51) )


Literatúra a Dosiahnuté výsledky:
- Kajan, Rozpoznávanie ľudských činností, Prednáška HNS, FEI STU Bratislava, 2025, [Prezentacia_Detekcia_ludskecinnosti_HNS_Kajan](document/rozpoznavanie_ludske_cinnosti.pdf)

