# electroporator
This is an instruction how to build electroporator for small algae.

**First, please build and use the circuit board at your own risk.**
**High voltage is very dangerous!**

This is designed for research use only.

# Basic function of each board
1.  **Arduino Due**
    - This generates main pulse sequence and constant voltage from two analog ports.

1. Switch and LED board
    - This start the program on Arduino Due and show when the pulse sequence starts.

1. OpAmp board
    - This calculates subtraction between two analog outputs from Arduino pre-amplifies the pulse sequence in order to use APEX PA92 range at most.
 
1. Power OpAmp APEX PA92 on EK16 kit.
    - Amplifying the sequence for electroplating cuvette.
    - Available from several electric parts web sites, as below.
        - PA92: https://www.mouser.com/ProductDetail/Apex-Microtechnology/PA92?qs=TiOZkKH1s2ScWh%2FYEqqirA%3D%3D
        - EK16: https://www.mouser.com/ProductDetail/Apex-Microtechnology/EK16?qs=TiOZkKH1s2QhV33E80pcCw%3D%3D
        
