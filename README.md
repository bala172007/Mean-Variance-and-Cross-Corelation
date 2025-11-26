# MEAN-AND-VARIANCE-USING-SCILAB

#AIM:

To write a program for mean, variance and cross correlation in SCILAB and verify the output.

#EQUIPMENTS Needed

· Computer with i3 Processor
· SCI LAB

#Algorithm

1. Define the Function: Specify the function you want to simulate. For example, f(x)=sin⁡(x)f(x) = \sin(x)f(x)=sin(x) or any other function.

2. Generate Sample Points: Decide on the range and the number of sample points. Generate these sample points within the desired range.

3. Evaluate the Function: Compute the function values at each of these sample points.

4. Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the mean and variance of the computed function values.

5. Display Results: Output the computed mean variance and Cross Correlation


#PROCEDURE

· Refer Algorithms and write code for the experiment.

· Open SCILAB in System

· Type your code in New Editor

· Save the file

· Execute the code

· If any Error, correct it in code and execute again

· Verify the generated results

#PROGRAM
```
function X=f(x)
z=3*(1-x)^2;
X=x*z;
endfunction
a=0;
b=1;
EX=intg(a,b,f); 
disp('Mean:',EX) ;

function X=g(x)
z=3*(1-x)^2;
X=x^2*z
endfunction 
a=0;
b=1;
EX2=intg(a,b,g); 
vX2=EX2-(EX)^2;
disp('Variance',vX2);




```
#OUTPUT:

i) Mean of X = 0.025
 
 Mean of Y = 0.37500



#Cross Correlation

Type in the reference sequence = [1 2 3 4 5 6 7 8]


Type in the second sequence = [2 1 3 5 6 3 5 9]



 #Calculation:
 ![WhatsApp Image 2025-11-26 at 15 46 49_0546c05e](https://github.com/user-attachments/assets/669d13a6-f8e2-4f08-a896-3c23ddfad575)



RESULT:

Thus the mean , variance and cross correlation are executed in Scilab and output is verified.
