# RBC #

## The dataset ##

The RBC corpus presents data extracted from 21 recordings of select movements of Brahms’ Cello Sonatas. For easier navigation in the corpus, the movements have been labelled according to their opus number followed by a lowercase roman numeral indicating their position within each composition.  

In the repository, scores, scape plots and performance metadata can be found. Scores are offered in PDF, MIDI, musicXML, .musx and .mscx formats. In order to facilitate navigation, .mscx scores contain note numberings for each part (piano or cello) separately. Metadata for each recording are organized by measurement unit:
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

File names in the dataset always follow a standardized format. For data obtained on the basis of note onsets, this is: movement-recording_abbreviation-NoteParameter-instrument. For data on  the basis of beats: movement-recording_abbreviation-parameter-measurement_unit. Spaces are avoided and, when necessary, two words forming a single item are united by an underscore (_).

In total, the RBC dataset contains 2725 files:

| Piece | Scores | Sonic Visualiser files | .txt files | .png files |
| ------ | ------ | -------- | ----- | ----- |
| Op. 38i | 5 | 4 x 20 = 80 | 19 x 20 = 380 | 9x 20 = 180 |
| Op. 38ii | 5 | 4 x 20 = 80 | 19 x 20 = 380 | 9x 20 = 180 |
| Op. 38iii | 5 | 4 x 20 = 80 | 19 x 20 = 380 | 9x 20 = 180 |
| Op. 99i | 5 | 3 x 15 = 45 | 14 x 15 = 210 | 9 x 15 = 135 |
| Op. 99ii | 5 | 3 x 15 = 45 | 14 x 15 = 210 | 9 x 15 = 135 |
| Total | 25 | 330 | 1560 | 810 |

## Expansion of the dataset ##
It is expected that data from the same 21 recordings of the third and fourth movements of Brahms’s Op. 99 will be uploaded to the repository by the end of 2021. Similarly, data from further recordings will be added in the future. In the hope of creating a collaborative repository too, the RBC affords expansion to host data extracted from recordings of other compositions by Brahms. The Violin Sonatas Opp. 78, 100 and 108 are contemplated as the first step in that direction. 

## Use of the dataset ##
All files are provided under a [Creative Commons Attribution Non-Commercial Share-Alike 4.0 (CC BY-NC-SA 4.0)] (https://creativecommons.org/licenses/by-nc-sa/4.0/) license.
