# Logisim-Circuit

LRU circuit that takes in read and write requests from a given memory and address


# How it works

To open the cache circuit, you have to download logisim-evolution and open the circuit file in that program.

Open the cachegrader and reload the cache circuit by right clicking the Cache folder on the left side

With the Test folder, you have to correctly input the data into their respective place

For example:

* To note, you have to input the files with corresponding names
* In the InputGeneratorCircuit, right click the ROM and press load contents. Load one of the inputs like seq_read1.txt
* In the main circuit, right click the RAM where it says Load the contents of memory here and press edit contents
  * Input a memory file such as seq_mem.txt
* In CheckerCirc right click the ROM and press load contents. Load the solution file such as seq_read1_seq_mem_sol.txt
* To highlight, the files that you input must correlate with each other
  * In this example, the three files all had to do with sequential memory and reading the files
