SharcCal
========

--- Calibration suite for SHARC ---


Current Functionality :-
1. Charge matrices
2. Fitted charge spectra
3. Centroid matrices
4. Calculated energy matrices
5. Calibration graphs


To Do :-
1. Multigraphs with separate fits
2. Combined graphs with global fit
3. Fit coefficient & chi2 matrices
4. Kinematic energy matrices
5. Excitation energy matrices (grouped, by using TH1::Add for individual sections)
6. Appending input file (only possible with blank fields, so no overwriting)


Open Questions :-
1. Enable full detector (source) calibration? This simply means that we loop over all det/fs/bs as opposed to downstream box.
2. 4-1 split canvas with the sections of sharc as a TH2F, where the color of a pixel represents some status
3. Pad Calibration 
