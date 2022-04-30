# Welcome to GENDC Program Matlab App


## Requirements
* MATLAB
* 552_library.csv
* Circuit in .csv or .txt format
* Own library in .csv format with fields: Name, Seq, Type, Repressed_by, Produces, Strength

## Initialization 
To run please open Matlab and press on the Apps button at the top bar. From there click on “open file” button and choose genDC.mlapp. Afterwards, please make sure that your 552_library.csv file is in the same directory as the code. This file is our standard library that will be imported by the program.

## How to run
* To run, press the Green Arrow at the top bar.
* You will see a blue GUI loading. When it loads, choose your file type and then on import circuit button and choose your circuit file. 
* The GUI screen should say that circuit was imported.
* If you want to add your own library please click on Import your own library button and choose your library.
* The GUI screen should say that your library was imported.
* Afterwards click the Run button and wait. If the program is done running you will see either error messages pop up in the GUI or a message saying “Design has no flaws”.
* Lastly the tick marks will appear for error types for which errors were identified in your circuit.
* If you desire, you can export these erros into a .txt file by clicking the Export .txt button. You can also name the filename for that. 
