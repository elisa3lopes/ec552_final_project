# Welcome to GenDC!

### What is GenDC
GenDC is a MATLAB App that takes in a circuit, analyzes the circuit based on a library of rules, and outputs warnings and suggestions for a synthetic biologist to use to improve his or her design. The program can also optionally take in a separate library of parts, allowing the user to define new parts and still have them checked for errors. 

### Why GenDC
The goal of our program is to allow for automatic testing of large complex synthetic biology circuit designs that would be too tedious to check by hand. It can be used by experienced and novice synthetic biologists alike to reduce the risk of failure and waste of resources when the circuit is actually implemented biologically. Additionally, the modular functions that make up the library of rules allows for more common failure mode checkers to be easily added in future development of the program. The major software components of GENDC are as follows: a user-friendly GUI, a library of rules, and a library of parts. 

## Requirements
* MATLAB
* 552_library.csv
* Circuit in .csv or .txt format
* Own library in .csv format with fields: Name, Seq, Type, Repressed_by, Produces, Strength

## Running GenDC

### Initialization 
To run please open Matlab and press on the Apps button at the top bar. From there click on “open file” button and choose genDC.mlapp. Afterwards, please make sure that your 552_library.csv file is in the same directory as the code. This file is our standard library that will be imported by the program.

### How to run
* To run, press the Green Arrow at the top bar.
* You will see a blue GUI loading. When it loads, choose your file type and then on import circuit button and choose your circuit file. 
* The GUI screen should say that circuit was imported.
* If you want to add your own library please click on Import your own library button and choose your library.
* The GUI screen should say that your library was imported.
* Afterwards click the Run button and wait. If the program is done running you will see either error messages pop up in the GUI or a message saying “Design has no flaws”.
* Lastly the tick marks will appear for error types for which errors were identified in your circuit.
* If you desire, you can export these erros into a .txt file by clicking the Export .txt button. You can also name the filename for that. 
