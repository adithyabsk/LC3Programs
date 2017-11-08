# LC3Programs

## General Note
Note make sure to open the PennSim jar within the folder where the code exists.  
```bash
cd ~/PATH/TO/LC3/ASM/
java -jar ../PennSim.jar
```  

Inside the PennSim applicaton run:  

```bash
script {PROGRAM_NAME}_script.txt
```

## AddOne Program
![AddOddDemo](Screenshots/AddOddDemo.png "Screenshot of output from AddOdd")
This program adds all the odd numbers between two user inputs and prints out the sum. The program can take each input from 1-99 and halts if the second number is less than the first number. Jump statements were not allowed during the implementation of the program and resulted in the quirky implementation using "routing" unconditional branch sections.
