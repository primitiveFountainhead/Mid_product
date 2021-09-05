# Generate Pseudo Random Numbers using mid-product method

The  mid-product  technique 
starts by selecting two seeds X0 and X0’ each 
containing the same number of digits D. Now, multiply 
X0  by  X0’  to  get  a  number  Ui.  Set  X1  equal  to  the 
middle D digits of U1 with the placement of appropriate 
decimals to obtain R1. Next multiply X1 by X0 to obtain 
U2, set X2 equal to the middle D digits of U2. Place the 
appropriate  decimal  to  obtain  the  next  random  number 
R2.Repeat  the  above  process  until  the  required  number 
of  random  numbers  is  generated.

Here we will generate a graph (finite state diagram) which is described as follows:
- The starting node (green one) indicates the initial two seeds 
- Red node indicates the final node where the graph starts to go in a loop
- Each node indicates the new seed value
- Each vertex indicates the product of two seed values

# Included Files
- A PDF file with answers to certain questions given
- A jupyter notebook containg code to do mid-product and generate graph
- An example graph
