# Project Title: Enhancement-of-RC5-Algorithm

# Introduction:
The arrival of many technologies for digital communication is rapidly increasing which has thereby also increased the need of security.
Hence various cryptographic algorithms need to be taken into consideration to secure the data from hackers, cybercriminals .
 IDEA – first choice for data encryption.
 DES (Data Encryption Standard) is one such encryption algorithm used mainly in financial and commercial applications.
 AES (Advanced Encryption Standard) , RC5 (Rivest Cipher 5), RSA : These are some of the popular encryption algorithms that can e used for security purposes.

Our main focus is on RC5
RC5:
Symmetric key block cipher algorithm.
One of the important feature is to use data dependent rotations
Complex key schedule and consists of modular functions.
Simple algorithm to understand.
Encryption and decryption expand the randomised key into 2(r+1) words where r is number of rounds ; is done sequentially  

# Objective: 
The aim is to reduce the total computation time needed to complete the process by parallelizing the algorithm using the concept of multi-threading. The complexity, data structures and the overall procedure of the algorithm would remain constant.

We shall enhance the performance through parallel approach and show the difference between the time complexity of both serial and parallel approach.
Here we have focused on RC5 encryption algorithm and are going to show both its serial and parallelized approach.

# Proposed System:
Considering the problem definition:
The algorithm steps as well as the pre-processing can be parallelized along with the instruction 
 The algorithm steps cannot be parallelized but pre-processing can be parallelized along with the instruction. 
 Neither the algorithm steps nor the pre-processing can be parallelized but instructions can be parallelized.
 These will help in parallel execution of the RC5 encryption algorithm using Open MP.
