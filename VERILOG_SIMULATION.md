# FUNCTIONAL SIMULATION
**For Ubuntu**

 Open your terminal and type the following to install iverilog and GTKWave
 ```
 $   sudo apt get update
 $   sudo apt get install iverilog gtkwave
 ```

![veena1](https://github.com/Veena-04/veena/assets/145828292/6ea9f733-d413-4ccd-9010-dba74838af65)



- **To clone the repository and download the netlist files for simulation, enter the following commands in your terminal.**

 ```
 $ git clone https://github.com/Veena-04/veena
 $ cd Documents
 $ cd hello
```
![veena2](https://github.com/Veena-04/veena/assets/145828292/e72b794e-6ecc-4088-ad3d-f0239f20bfbe)

- **To simulate and run the Verilog code, enter the following commands in your terminal.**

```
$ iverilog -o hello hello.v hello_tb.v
$ ./hello
```



- **To see the output waveform in gtkwave, enter the following commands in your terminal.**

`$ gtkwave hello.vcd`



  Full 5-stage instruction pipeline and pc-increment description Waveform
  
![veena3](https://github.com/Veena-04/veena/assets/145828292/0d7dc2c9-929f-4ec0-8932-09bd9713f3df)
![veena4](https://github.com/Veena-04/veena/assets/145828292/69a41084-ae52-4067-9fd9-662f03d60918)

![veena5](https://github.com/Veena-04/veena/assets/145828292/b347f214-969c-4c9a-8aee-44bc82bca118)





