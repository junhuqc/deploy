# Some useful Tips
---------------------

* Generate PEM key

  ```bash
  $ openssl genrsa -des3 -out dev.pem 2048 (pass phrase encrypted) # or
  $ openssl genrsa -out private_key.pem 2048
  ```

* Output public key for SSH
  ```bash
  ssh-keygen -y -f private_key.pem > public_key.pub
  ```
