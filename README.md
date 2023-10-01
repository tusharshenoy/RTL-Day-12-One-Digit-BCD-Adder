# RTL-Day-12-One-Digit-BCD-Adder

### Problem Statement: Implementing a one Digit BCD Adder using structural Style.
### Theory: 
BCD stands for binary coded decimal. It is used to perform the addition of BCD numbers. A BCD digit can have any of ten possible four-bit representations. Suppose, we have two 4-bit numbers A and B. The value of A and B can vary from 0(0000 in binary) to 9(1001 in binary) because we are considering decimal numbers. 


 ![image](https://github.com/tusharshenoy/RTL-Day-12-One-Digit-BCD-Adder/assets/107348474/9126665c-7b97-496a-8664-b87bfb3cc3c6)


The output will vary from 0 to 18 if we are not considering the carry from the previous sum. But if we are considering the carry, then the maximum value of output will be 19 (i.e. 9+9+1=19). When we are simply adding A and B, then we get the binary sum. Here, to get the output in BCD form, we will use BCD Adder.


 
  ![image](https://github.com/tusharshenoy/RTL-Day-12-One-Digit-BCD-Adder/assets/107348474/b5f5a90e-897c-4b63-89b7-3d76304eb7e7)




  ![image](https://github.com/tusharshenoy/RTL-Day-12-One-Digit-BCD-Adder/assets/107348474/2e9a882d-e53d-4241-979d-f99b474f94a6)

 





### Design of Correction Logic
 

 ![image](https://github.com/tusharshenoy/RTL-Day-12-One-Digit-BCD-Adder/assets/107348474/3c8790fa-80db-46d8-9826-7de0c856bff9)


 ![image](https://github.com/tusharshenoy/RTL-Day-12-One-Digit-BCD-Adder/assets/107348474/6ad9afcd-a63c-4c93-82b3-c4fb680852ba)
 


![image](https://github.com/tusharshenoy/RTL-Day-12-One-Digit-BCD-Adder/assets/107348474/f98f8e16-fb3c-4a01-9bf5-3d7401c1854d)
 
#### FIG: Block Diagram of one Digit BCD Adder


### Schematic:


  ![image](https://github.com/tusharshenoy/RTL-Day-12-One-Digit-BCD-Adder/assets/107348474/45ee4b1f-5ed2-4d1b-ac58-7d2a3d1d5596)

#### FIG: Full adder Schematic


  ![image](https://github.com/tusharshenoy/RTL-Day-12-One-Digit-BCD-Adder/assets/107348474/d2467ab3-d477-4b20-8203-945ba1963bdd)

#### FIG: Parallel adder/Four Bit Adder Schematic


 ![image](https://github.com/tusharshenoy/RTL-Day-12-One-Digit-BCD-Adder/assets/107348474/7ae070f2-c74b-49f1-b37a-6dbfa8a23434)

#### FIG: One Digit BCD Adder Schematic

### Simulation Output: 

 ![image](https://github.com/tusharshenoy/RTL-Day-12-One-Digit-BCD-Adder/assets/107348474/34162c20-558b-4a3d-96b8-4b81f0ae3b78)


References:-
1. [BCD Adder in Digital Logic](https://www.geeksforgeeks.org/bcd-adder-in-digital-logic/)
