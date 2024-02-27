**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& (sum1ton.c is the file name)
If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****
![leafpad_install]![task3veena1](https://github.com/Veena-04/veena/assets/145828292/6a47a7d8-8894-423d-aa8c-2a6ed29a6fe0)


****Step 2: Writing the C code in the leafpad editor** using the following command

**leafpad sum1ton.c&**
![Leafpad_editor]![task3veena2](https://github.com/Veena-04/veena/assets/145828292/4b4e6e22-9408-4d73-b47a-202a50c8eef6)


**Step 3: After writing the C code save the editor by Ctrl+s**

**Step 4: Check for the errors by using the following command(compilation step)**

**gcc sum1ton.c**

**Step 5: Check the output by using the command**

**./a.out**
![C Code Execution with results ]![task3veena3](https://github.com/Veena-04/veena/assets/145828292/330d1df8-1eb3-43d3-9fa5-5d52a484dd76)


**The results will be displayed as** 

**Sum of numbers from 1 to 500 is 125250**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**
![view in the C code in notepad]![task3veena4](https://github.com/Veena-04/veena/assets/145828292/1093c35e-68c3-4ec4-ba6b-c96903feedbb)


**Step 2: Compile the code in riscv using the following command**

**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**

![view the directory contents]![task3veena5](https://github.com/Veena-04/veena/assets/145828292/77a93534-e72c-4676-965f-aef7186cac94)




**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**

![checking instructions_in_main_C_Code_15_instructions]

![checking instructions_in_main_C_Code_15_instructions_highlighted]


**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

![12 instructions with Ofast](https://github.com/Abdulbitm/Abdul/assets/160620896/f2ebdc19-c3a6-494d-a25d-6d71c2811440)



![12 instructions with Ofast_1]![task3veena7](https://github.com/Veena-04/veena/assets/145828292/5582ceaa-7e1f-4124-95e3-144c90bd6cd3)






