# The Recorded Brahms Corpus (RBC) #

## The dataset ##

The RBC corpus presents data extracted from 21 recordings of select movements of Brahms’ Cello Sonatas. For easier navigation in the corpus, the movements have been labelled according to their opus number followed by a lowercase roman numeral indicating their position within each composition.

### Structure and size of the dataset ###

In the repository, a first initial division is to be found among the various movements analysed, and, subsequently, a second one between Scape Plots, Scores and Data. In each of this folders, specific subfolders for each of the recordings are included. Data for each recording are organised by measurement unit. In each of the folders, the corresponding Sonic Visualiser file is provided, along with .txt files (see below).


File names in the dataset always follow a standardised format. For data obtained on the basis of note onsets, this is: movement-recording_abbreviation-NoteParameter-instrument. For data on  the basis of beats: movement-recording_abbreviation-parameter-measurement_unit. 

In total, the RBC dataset contains 2725 files:

| Piece | Scores | Sonic Visualiser files | .txt files | .png files |
| ------ | ------ | -------- | ----- | ----- |
| Op. 38i | 5 | 4 x 20 = 80 | 19 x 20 = 380 | 9x 20 = 180 |
| Op. 38ii | 5 | 4 x 20 = 80 | 19 x 20 = 380 | 9x 20 = 180 |
| Op. 38iii | 5 | 4 x 20 = 80 | 19 x 20 = 380 | 9x 20 = 180 |
| Op. 99i | 5 | 3 x 15 = 45 | 14 x 15 = 210 | 9 x 15 = 135 |
| Op. 99ii | 5 | 3 x 15 = 45 | 14 x 15 = 210 | 9 x 15 = 135 |
| **Total** | **25** | **330** | **1560** | **810** |

### The recordings ###

The RBC corpus offeres data from the following recordings:

| Abbreviation | Cellist | Pianist | Year | Label | Title |
| ------------| -------| --------| ------- | ------ | ------ |
| C/H(36) | Pau Casals | Mieczysław Horszowski | 1936 | HMV, DB 3059-62 | _Brahms: Sonata in F major (F Dur)_ | 
| C/H(36) | Pau Casals | Mieczysław Horszowski | 1958 | | |
| DP/B | Jacqueline du Pré | Daniel Barenboim | 1968 | Angel Records, S-36544 | _Brahms: The Two Sonatas for Cello and Piano_ | 
| F/B | Pierre Fournier | Wilhelm Backhaus | 1955 | Decca, LXT 5077 | _Sonata No 1 in E MINOR for ‘cello and piano – Sonata No 2 in F MAJOR for 'cello and piano – BRAHMS_|
| F/vdP | Emmanuel Feuermann | Theo van der Pas | 1934 | Columbia Masterworks, Set No. 236 | _Brahms: Sonata for Cello and Piano No. 1 In E minor, Op. 38_ |
| G/G | Karine Georgian | Pavel Giglilov | 1994 | Biddulph Recordings, 744718101429 | _Brahms: Cello Sonatas (Op. 38 & 99)_|
| G/Gr | Sol Gabetta | Hélène Grimaud | 2012 | Deutsche Grammophon, 0289 479 0965 1 | _Duo_|
| G/Gu | Anne Gastinel | François Frédéric Guy | 1999 | Naïve (Valois), V4817 | _Johannes Brahms: Sonates pour Violoncelle & Piano_|
| I/H | Steven Isserlis | Stephen Hough | 2005 | Hyperion, BE114A0B | _Johannes Brahms: Cello Sonatas_|
| M/A | Yo-Yo Ma | Emanuel Ax | 1991 | Sony Classical SK 48191 | _Brahms: Sonatas for Cello & Piano Opp. 38, 99 and 108_|
| M/G | Mischa Maisky | Pavel Gililov | 1998 | Deutsche Grammophon, 0289 459 6772 1 GH | _Brahms: Die Cellosonaten – Lieder Ohne Worte_ |
| M/L | Truls Mørk | Juhani Lagerspetz | 1998 | Virgin Classics, VC 5 45052 2 | _Brahms: Cello Sonatas – Song Transcriptions_|
| M/P | António Meneses | Maria João Pires | 2013 | Deutsche Grammophon, 0289 479 0965 1 | _The Wigmore Hall Recital_ |
| P/N | Asier Polo | Eldar Nebolsin | 2019 | Ibs Classical IBS82019 | _Brahms. Cello Sonatas_ |
| P/R(36) | Gregor Piatigorsky | Arthur Rubinstein | 1936 | HMV, DB 2952-54 | _Brahms: Sonata No. 2 in E minor, Op. 38_|
| P/R(66) | Gregor Piatigorsky | Arthur Rubinstein | 1966 | RCA Red Seal, ARL1-2085 | _Brahms. Sonatas for Cello and Piano – E Minor Op. 38 / F Major Op. 99_|
| P/S | Gregor Piatigorsky | Reginald Stewart | 1947 | Music & Arts, CD 644 | compiled in _The Art of Gregor Piatigorsky (1903-1976)_|
| P/V | Boris Pergamenschikow | Lars Vogt | 2002 | EMI Classics, 557526 | _Brahms – Schumann – Works for Cello and Piano_|
| R/S | Mstislav Rostropovich | Rudolf Serkin | 1983 | Deutsche Grammophon, 410 510-2 | _Johannes Brahms: Die Cellosonaten – The Cello Sonatas_|
| S/B | János Starker | Abba Bogin  | 1951 | Period Records, SPL 593 | _Brahms: Sonatas for Cello and Piano_|
| S/S | János Starker | György Sebȍk | 1964 | Speaker Corners/Mercury Records, SR90392 |  _Brahms: Sonatas for Cello and Piano_|


### The data ###  

In the repository, scores, scape plots and performance metadata can be found. Scores are offered in PDF, MIDI, musicXML, .musx and .mscx formats. In order to facilitate navigation, .mscx scores contain note numberings for each part (piano or cello) separately. Data for each recording are organised by measurement unit:
1. Op. 38i: note/ crotchet beat / minim beat / bar
2. Op. 38ii: note / quaver beat / crotchet beat / bar
3. Op. 38iii: note / crotchet beat / minim beat / bar 
4. Op. 99i: note / crotchet beat / bar
5. Op. 99ii: note / semiquaver beat / quaver beat / crotchet beat / bar 

In each of the metadata folders, the corresponding Sonic Visualiser file is provided, along with .txt files for the 5 parameters which the corpus evaluates:

| Parameter | Abbreviation | Unit |
|---------- | ------------ | ----|
| Beat and note onsets | tappings/onsets | s |
| Beat and note durations | duration | s |
| Tempo fluctuations | tempo | bpm |
| Continuous dynamic variations | smoothed_power | dB |
| Dynamic values at specific instants | dB_per_beat | dB | 

All .txt files present the same internal structure:
-	column 1: instant (in second) at which the measurement was taken
-	column 2: value for each given parameter
-	column 3: instant label as bar.beat or as note number

Exceptionally, smoothed_power files lack the third column, as measurements are made on a continuous basis and not at specific beat instants; dB_per_beat files lack column 2 as its position value is contained in column 1.




## Expansion of the dataset ##
It is expected that data from the same 21 recordings of the third and fourth movements of Brahms’s Op. 99 will be uploaded to the repository by the end of 2021. Similarly, data from further recordings will be added in the future. In the hope of creating a collaborative repository too, the RBC affords expansion to host data extracted from recordings of other compositions by Brahms. The Violin Sonatas Opp. 78, 100 and 108 are contemplated as the first step in that direction. 

## Use of the dataset ##
All files are shared under a [Creative Commons Attribution Non-Commercial Share-Alike 4.0 (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.
