-----------------------------------------------------------------------------------------------
README
-----------------------------------------------------------------------------------------------

Important Note : The program uses Python 3. 

-----------------------------------------------------------------------------------------------


Run program with the parameters of the curve as follows:

Example run statement:

python ECDH.py -a 2 -b 2 -p 17 -x 5 -y 1


-------------------------------------------------------------------------------------------------

a,b - parameters of the curve y^2 = x^3 + ax + b
p   - modulo prime for the curve (Ensure it is a prime number!)
x,y - Generator coordinates (Ensure it is a point on the curve specified by a and b)

-------------------------------------------------------------------------------------------------

Output:

Generates a (private key, public key) pair for two users Alice and Bob.
Generates a shared key to be used as the session key. Can be hashed to use as symmetric key.
Checks whether the shared key for both users are the same.

-------------------------------------------------------------------------------------------------

Future improvements and additions:

- Add random prime generator of n-bit length
- Implement hashing of shared key
- Message encryption and decryption