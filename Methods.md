After engraving the scores in Finale26[17] and exporting them in various formats (see above), ground-truth performance annotations were obtained in Sonic Visualiser[18] by:
-	numbering the notes for the cello and the piano parts separately (for clearer visualization, numberings for only the first notes in each bar are given). Numberings are included in the MuseScore3[19] (.mscx) files as chord symbols.
-	importing the desired track in Sonic Visualiser. The corresponding wave form appears on the screen (layer 2 in SV files).
-	generating a spectrographic image (layer 3).
-	tapping the recording while it is being played at normal – or the most convenient – speed to determine beat/note onsets. Tappings appear in the form of vertical lines that cover the whole vertical space of the wave form. Measurement units at this stage are the smallest beat possible (layer 4, in white) and notes (in the relevant files, layers 5 and 6; in bright purple for the piano and bright orange for the cello).
-	adjusting provisional tappings to the start of each tapped note as visualized in the spectrogram (Cook, 2009).
-	aurally checking the accuracy of the tappings by playing the track at a significantly slower speed and relocating the lines when necessary. For beat measurements, when asynchronies between the cello and the piano occur, tappings were adjusted according to the rhythmically most active part, normally the piano. For accurate note measurements, each instrumental part was annotated individually.
-	renumbering the tappings to show bar and beat number within bars (they are given in the form of bar.beat annotations) or note numbers.
-	exporting tapping data as .txt files.

Subsequently, additional timing data were automatically obtained by creating, for each measurement unit, two Time Values layers[20] to yield information regarding:
-	beat duration (in seconds) (layer 5 for beat measurements; layer 7 for note tappings)
-	tempo (bpm) from the previous item (layer 6, in orange in beat-based files; layer 8 in note-measured ones). Data were exported as .txt files. 

In the case of beat measurements only, further data were automatically extracted by:
-	creating a Smoothed Power layer (no. 7, in purple) and exporting data as a .txt file. 
-	aligning smoothed power data and tappings. For that, an open-source Dyn-a-matic tool[21] was employed; data were saved as .txt.
-	obtaining tappings for bigger beat units by deleting undesired tapping lines. Time instants are re-numbered. Corresponding SV and .txt files for beat onsets, durations, tempo, and dynamics data were created.
-	generating separate scape plots for tempo and dynamics separately. These were obtained in an open-source Scape Plot Generator tool[22] from dB-per-beat data. Images were stored as .png files. They were subsequently merged into a diamond-shaped figures in Microsoft® Paint, the upper triangle showing tempo fluctuations and the lower one referring to dynamics. Smallest measurement units were always used, and scape plots were generated without flip colour and using 3 different degrees of smoothing (0.1, 0.5 and 0.9) respectively. 
