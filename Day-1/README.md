## What is Linear Algebra? 
 Linear algebra is a branch of mathematics focused on vectors, vector spaces, linear transformations, and systems of linear equations, essentially the algebra of lines and planes in higher dimensions, providing tools to model 
and solve complex problems in science, engineering, computer graphics, and especially modern machine learning by representing data as vectors and matrices for efficient computation. 

### 1.1 Organizing Information 
Example:  (Of organizing and reorganizing information)
     You own stock in 3 companies: Google, Netflix, and Apple. The value V of your
stock portfolio as a function of the number of shares you own sN; sG; sA of these
companies is 24sG + 80sA + 35sN :

<img width="256" height="56" alt="image" src="https://github.com/user-attachments/assets/cfc65b77-85f3-4b39-9918-dea2e2e02127" />

The column of three numbers is ambiguous! Is it is meant to denote
• 1 share of G, 2 shares of N and 3 shares of A?
• 1 share of N, 2 shares of G and 3 shares of A?

 Solution:   

 Step 1: Define the Variables
       sGs_GsG​ = number of Google shares
       sNs_NsN​ = number of Netflix shares
       sAs_AsA​ = number of Apple shares

Let the price per share be:
    pGp_GpG​ = price of Google share   
    pNp_NpN​ = price of Netflix share
    pAp_ApA​ = price of Apple share

Step 2: Express Portfolio Value as a Linear Combination
       
       The total value VVV of your portfolio is:  V=pG​⋅sG​+pN​⋅sN​+pA​⋅sA​

Step 3: Organize as Vectors and Matrix
        Represent shares and prices as vectors:
        
<img width="179" height="85" alt="image" src="https://github.com/user-attachments/assets/bae02140-54cd-43c9-91a0-389ae77b39ce" />
<img width="244" height="86" alt="image" src="https://github.com/user-attachments/assets/944a452d-8e38-493a-944e-8b8b2c808e96" />


Step 4: Reorganizing Information
         If you have multiple portfolios (say for different people), you can store them in a matrix:
         <img width="167" height="95" alt="image" src="https://github.com/user-attachments/assets/8694231b-eed2-4c09-ba32-f9a6c4b6618a" />

        
    
1.2 What are Vectors?




1.3 What are Linear Functions? . . . . . . . . . . . . . . . . . . . 
1.4 So, What is a Matrix? . . . . . . . . . . . . . . . . . . . . . . 
1.4.1 Matrix Multiplication is Composition of Functions . . . 
1.4.2 The Matrix Detour . . . . . . . . . . . . . . . . . . . . 
1.5 Review Problems . . . . . . .
