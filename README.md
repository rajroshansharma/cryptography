# cryptography
cracking passwords projects
1. Password cracking : 
   recovering a password from the hashed value.for eample : suppose a user forgotton it's password but he knows the hashed value of his pwd so he will use some technique to crack it.
   and rember it's password.

2. Password salting :
   In cryptography, a salt is random data that is used as an additional input to a one-way function that hashes data, a password or passphrase. Salts are used to safeguard passwords in 
   storage. Historically a password was stored in plaintext on a system, but over time additional safeguards were developed to protect a user's password against being read from the system.
   A salt is one of those methods.
   A new salt is randomly generated for each password. In a typical setting, the salt and the password (or its version after key stretching) are concatenated and processed with a 
   cryptographic hash function, and the output hash value (but not the original password) is stored with the salt in a database. 

3. Hash functions:
   it is a function in which if we pass any thing it will convert in into a particular form(alphanumrical or using special charcters).which gives it a diffrent id,from the original ones.

4. Password cracking tools:
   softwares like Aircrack,cain and abel,John the ripper,hashcat,hydra and many more.
   this software uses some sort of algorithm to crack the password and recover the data.
5. Password strength checker:
   a web app or a sofware that checks the strnght of your password and calculate the percentage of strength and show the results.
   there would be many parameters throuh which any pwd is judged the strength of the pwd.
   
