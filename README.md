# OSNOVE ELEKTROTEHNIKE Z JUPYTROM

 Dejan Križaj, 2019 

## Uvod
V tem Gitu je dodaten material za študij predmetov Osnove elektrotehnike 1 in 2. Material je v obliki Jupyter zvezkov, ki vključujejo tako tekst kot tudi enačbe in ključno - računalniško kodo. Ta je v obliki kratkih (ali daljših) programskih stavkov v programskem jeziku Python, ki omogočajo enostavno realizacijo bistvenih potreb predmeta - izračune in vizualizacijo. 

Zakaj Jupyter, zakaj Python? Če bi malo pobrskali po spletu, bi ugotovili, da Python postaja programsko orodje št. 1 na področju tehniških ved in popolnoma prevladuje na področju umetne inteligence, obdelave podatkov, ... Jupyter pa je okolje, ki omogoča integracijo teksta v html (ali poenostavljenem markdown) formatu z Latex formulami in Python kodo. Resen konkurent Juyptru bi lahko bil Matlab, ki se tudi zelo pogosto uporablja v tehniki. Je morda celo malo bolj preprost za uporabo, ni pa brezplačen in tudi ne omogoča Juypter oblike. Poleg tega Matlab ni ravno pravi programski jezik, medtem ko Python brez dvoma je - seveda s posebnostmi, ki jih ima vsak programski jezik. 

V našem primeru bomo Python uporabili bolj kot skriptni jezik, podobno kot Matlab, torej predznanje programiranja za uporabo Jupyter zvezkov ni potrebno. Ravno nasprotno, zvezki so koncipirani tako, da se sproti naučite tako osnovnih ukazov, ki omogočajo izračune in izrise, kot tudi nekaj osnov programiranja - for zanke, if stavki, funkcije in podobne zadeve.

Sploh pa, vsi relevantni izračuni so v zvezkih že narejeni. Lahko le prelistavate zvezke in študirate koncepte električnega in magnetnega polja ter vezij, skratka snov, ki jo obravnavata predmeta OE1 in OE2. Vizualizacija je ključna za pravilno razumevanje osnovnih konceptov. Poleg tega ste pa lahko tudi sami pri tem še bolj aktivni. Če imate Jupyter naložen na svojem računalniku ali pa uporabljate način oblačnega programiranja, lahko zvezke ne le prebirate pač pa tudi spreminjate, dopišete svojo kodo ali le spremenite parametre itd. In s tem se sproti učite tako elektrotehnike kot programiranja. 

In kot že rečeno, Jupyter in Python se uporablja tudi v praksi, tako v raziskovalnem delu kot v industriji. Zato vaše aktivnosti zagotovo ne bodo zaman in jih boste s pridom uporabili tudi v višjih letnikih in tudi kasneje. 

Še to: zaenkrat zvezki ne pokrivajo celotne snovi OE1 in OE2. Pravzaprav le večji del vezij pri izmeničnih signalih. Vendar, glavno je razumeti princip, če znaš narisati Tok in Naboj kot funkcijo časa, znaš narisati tudi Delovno moč kot funkcijo frekvence itd. 

Nekaj splošnega o Jupytru, kako zaganjati zvezke itd, si preberite v 
https://github.com/osnove/Dodatno/blob/master/Uporaba_Jupitra.ipynb

## Osnove elektrotehnike 1

* **OE:** Prikaz povezave med tokom in nabojem. **Jupyter:** Prvi izračun in izris z Jupytrom. Prikaz različnih možnih izrisov. Uporaba funkcije - prvič.  
https://github.com/osnove/Dodatno/blob/master/oe1_Q_i.ipynb [![oe1_Q_i](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/oe1_Q_i.ipynb)


## Osnove elektrotehnike 2

* **OE:** Prehodni pojav. Prikaz analitičnega izračuna. **Jupyter:** Prikaz simbolnega računanja z uporabo modula Sympy.  
https://github.com/osnove/Dodatno/blob/master/Primer_diff_enacbe_analiticno.ipynb  [![Primer_diff_enacbe_analiticno](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Primer_diff_enacbe_analiticno.ipynb)

* **OE:** Periodični signali: frekvenca, faza, srednja vrednost, efektivna vrednost ... **Jupyter:** Modul SciPy za tvorjenje signalov. 
https://github.com/osnove/Dodatno/blob/master/Periodicni_signali.ipynb  [![Periodicni_signali](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Periodicni_signali.ipynb)

* **OE:** Prehodni pojav. Prikaz numeričnega izračuna. **Jupyter:** Prikaz uporabe numeričnih metod z odeint. 
https://github.com/osnove/Dodatno/blob/master/Primer_diff_enacbe_numericno.ipynb  [![Primer_diff_enacbe_numericno](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Primer_diff_enacbe_numericno.ipynb)

* **OE:** Prehodni pojav RLC vezij - analitično in numerično. **Jupyter:** Prikaz uporabe analitičnih in numeričnih metod za reševanje diferencialnih enačb drugega red. 
https://github.com/osnove/Dodatno/blob/master/Primer_diff_enacbe_analiticno-numericno_RLC.ipynb   [![Primer_diff_enacbe_analiticno-numericno_RLC](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Primer_diff_enacbe_analiticno-numericno_RLC.ipynb)

* **OE:** Obravnava vezij s kompleksnim računom. Izris kompleksorjev v kompleksni ravnini. **Jupyter:** Uporaba kompleksnega računa. Zapis funkcije v modulu in njena uporaba.   
https://github.com/osnove/Dodatno/blob/master/Obravnava_vezij_kompleksni_racun.ipynb
 [![Obravnava_vezij_kompleksni_racun](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Obravnava_vezij_kompleksni_racun.ipynb)

* **OE:** Moč pri izmeničnih signalih. Časovni potek in prehod v obravnavo s kompleksorji. Navidezna, delovna in jalova moč. Dodatno: Lock-in metoda. **Jupyter:** Uporaba kompleksnega računa. Uporaba modula Pandas za delo s tabelami.  
 https://github.com/osnove/Dodatno/blob/master/Moc_izmenicni_signali.ipynb  [![Moc_izmenicni_signali](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Moc_izmenicni_signali.ipynb)

* **OE:** Resonančni pojav: obravnava v časovnem in frekvenčnem prostoru. Resonančna frekvenca, bočne frekvence, pasovna širina, kvaliteta vezja. **Jupyter:** Uporaba kompleksnega računa. Uporaba interaktivnih gradnikov (widgets). 
https://github.com/osnove/Dodatno/blob/master/Obravnava_resonancnega_pojava.ipynb
 [![Obravnava_resonancnega_pojava](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Obravnava_resonancnega_pojava.ipynb)
 
 * **OE:** Frekvenčne lastnosti tuljave, kondenzatorja in upora - analiza realnih elementov. Spice modeli. Kvaliteta, ekvivalentna serijska upornost ESR, itd. **Jupyter:**  
https://github.com/osnove/Dodatno/blob/master/Frekven%C4%8Dne_lastnosti_upora_kondenzatorja_tuljave.ipynb
 [![Frekven%C4%8Dne_lastnosti_upora_kondenzatorja_tuljave](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Frekven%C4%8Dne_lastnosti_upora_kondenzatorja_tuljave.ipynb)
 
  * **OE:** Filtri. Nizkoprepustni RC filter, mejna frekvenca, Bodejev diagram, decibeli, Butterworthov filter, Digitalni filtri **Jupyter:** SciPy modul za delo s filtri 
https://github.com/osnove/Dodatno/blob/master/Filtri.ipynb
 [![Filtri](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Filtri.ipynb)
 
 * **OE:** Nadgradnja analize impedance vezij - Impedančna spektroskopija. Uporaba v biotehnologiji in medicini. **Jupyter:** Uporaba modula Scipy za prileganje krivulje podatkom (fitanje po domače). 
https://github.com/osnove/Dodatno/blob/master/Impedancna_spektroskopija.ipynb
 [![Impedancna_spektroskopija](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Impedancna_spektroskopija.ipynb)

  * **OE:** Vrtilno magnetno polje. **Jupyter:** Izdelava animacije. 
https://github.com/osnove/Dodatno/blob/master/Vrtilno_magnetno_polje.ipynb
 [![Vrtilno_magnetno_polje](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Vrtilno_magnetno_polje.ipynb)
 
 * **OE:** Trifazni sistemi. **Jupyter:** Izdelava animacije. 
https://github.com/osnove/Dodatno/blob/master/Trifazni_sistemi.ipynb
 [![Vrtilno_magnetno_polje](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Trifazni_sistemi.ipynb)
 

## Dodatno

 * **OE:** Izdelava pravokotnega periodičnega signala. izdelava odvedljivega pravokotnega signala. Fourierova analiza (spekter). **Jupyter:** Uporaba modula scipy za izdelavo pravokotnega periodičnega signala.  Funkcije, for zanke, if stavki itd. FFT (Fast Fourier Transform za spektralno analizo signala) 
https://github.com/osnove/Dodatno/blob/master/Zglajen_pravokoten_signal.ipynb
 [![Zglajen_pravokoten_signal](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/Zglajen_pravokoten_signal.ipynb)

 * **OE:** Dodatni primeri uporabe modula Matplotlib za izris grafov **Jupyter:** Matplotlib 
https://github.com/osnove/Dodatno/blob/master/primer%20Matplotlib.ipynb
 [![primer%20Matplotlib](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/primer%20Matplotlib.ipynb)

 * **OE:** del impedančne spektroskopije **Jupyter:** Uporaba modula BeautifulSoup za zajem informacij (tabel, itd) iz spletnih strani in njihova obdelava z modulom Pandas. Uporaba interaktivnih gradnikov: spustni seznam, ..
https://github.com/osnove/Dodatno/blob/master/BeautifulSoup_Pandas.ipynb
 [![BeautifulSoup_Pandas](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/osnove/Dodatno/blob/master/BeautifulSoup_Pandas.ipynb)
