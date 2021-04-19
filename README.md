# Encrypt-Decrypt-data

##### To Generate gpg keypair, run : `gpg --generate-key` and follow the instructions

##### To list all public keys, run : `gpg -k`

##### To list all private keys, run : `gpg -K`


##### Example : 
![](https://raw.githubusercontent.com/varunelavia/Encrypt-Decrypt-data/main/Key-List-v2.png)

##### In above image, the key id is `2EAF3A12C4F47AFFDA376C08004E197503198231`

##### To export public key to a file, run : `gpg --output public.pem --export --armor --Key-ID--`

##### To export private key to a file, run : `gpg --output public.pem --export-secret-key --armor --Key-ID--` this is not recommended and should be done at own risk. Do keep private key at a safe place.




