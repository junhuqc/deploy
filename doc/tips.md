# Some useful Tips
---------------------

* Generate PEM key

  ```bash
  $ openssl genrsa -des3 -out dev.pem 1024 (pass phrase encrypted)
  $ openssl genrsa -out dev.pem 1024
  ```

* Output public key for SSH
  ```bash
  ssh-keygen -y -f private_key.pem > public_key.pub
  ```
