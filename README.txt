This was a project that was created by John Venditti, Joseph (Tyler) Dibartolo, and I, Gabriel Gomez. The class we did this for was our Data Structures and Algorithms class, and it pertains to flow networks as the repo name suggests. This was an admittedly difficult project, but one that we were able to solve. In this project, one can see the generation of flow networks, analysis of those flow networks using Ford-Faulkerson method and augmenting necessary paths, and an analysis directory which was used for helping determine run time. 

In order to compile and run our program, all you have to do is run the following command from terminal while in the "src" (was originally "source" directory until an error occurred with GitHub) folder and ensure that you have GraphViz along with python3 on your computer. The reason you need GraphViz is because it supplies the "dot" application which can create .png files based off .dot files. 

Instruction to run:
 “python3 main.py”
 
 The analysis folder contains code used to generate our charts and determine runtimes. The generators in that folder are more deterministic for smaller sizes, which is why we did not use them for the main portion of this assignment,

Disclaimer:
 The program will create 10 .dot files, but will not automcatically convert those files to their .png equivalent. In order to create a .png file based of the .dot files, you must run "dot -Tpng fileName.dot -o outputFile.png" within the terminal, while in the "input_graphs" directory or "output_graphs" directory. For example, if you wish to convert the .dot file of graph1, in the terminal you would write "dot -Tpng graph1.dot -o graph1.png"
