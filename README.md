# RBC
The RBC corpus presents data extracted from 21 recordings of select movements of Brahms’ Cello Sonatas. For easier navigation in the corpus, the movements have been labelled according to their opus number followed by a lowercase roman numeral indicating their position within each composition.  

A first initial division is to be found among the various movements analyzed, and, subsequently, a second one between Scape Plots and Sonic Visualiser Data. In each of this folders, specific subfolders for each of the recordings are included.

For each movement, scores in .musx, .mscx and PDF formats are provided, along with MIDI and .musicxml files. The MuseScore file contains all notes numbered for both the cello and the piano separately.

The scape plots files are organised, for each recording, in the form of two subfolders hosting .png files for dynamics and tempo data respectively. In the master folder, merged plots are stored too. 

Sonic Visualiser Data for each recording are organized by measurement unit, from the bar to precise note onsets in the cello and the piano parts. In each of these folders, the corresponding Sonic Visualiser file is provided, along with several.txt files in a ‘Data’ subfolder.
Those 5 file types include data of the 5 parameters which the corpus evaluates. These are:
1.	dynamic values at specific instants (dB_per_beat), in dB
2.	beat durations (duration), in seconds
3.	continuous dynamic variations (smoothed_power), in dB
4.	tempo fluctuations (tempo), in bmp (beats per minute)
5.	beat tappings (tappings), in seconds

For the note measurements, only onset (file no. 5) and duration (no. 2) measurements are provided, for both the cello and the piano parts.

Files nos. 1-2 and 4 present the same internal structure:
-	column 1: instant (in second) at which the measurement was taken
-	column 2: value for each given parameter
-	column 3: instant label as bar.beat
Nos. 3 and 5 files follow the same structure as Nos. 1-2 and 4, yet no. 3 files (smoothed_power) lack the third column, as measurements are made on a continuous basis and not at specific beat instants, and files nos. 5 lack column 2 as its position value is contained in column 1 already.
