# CipherReveal
CipherReveal is a simple tool that cracks hashed passwords by comparing them with hashes from a wordlist. It supports hash types like MD5, SHA-1, and SHA-256. Just input the hash, hash type, and wordlist, and it will find the original password. 
HashBreaker Pro
A powerful tool designed to brute-force hashes using a wordlist of your choice.


# CipherReveal Pro

A powerful tool designed to brute-force hashes using a wordlist of your choice.

## **Key Features**
- **Supports Multiple Hashing Algorithms:** Decode hashes from md5, sha1, sha256, and more.
- **Command-Line Friendly:** Simple and easy-to-use interface for all levels.
- **Error Handling:** Detailed feedback to assist with troubleshooting.

## **Requirements**
- Python 3.x

## **How to Use**
Run the hash-breaking tool by executing the following command:


## Input Parameters

- `--hashvalue`: The target hash you want to break.
- `--hashtype`: The hash algorithm used (e.g., md5, sha1, sha256, etc.).
- `--wordlist`: File path to the wordlist used for attempting brute-force.

## Sample Command

To crack an md5 hash using the wordlist `passwords.txt`, run:

python hashbreaker.py --hashvalue 7052cad6b415f4272c1986aa9a50a7c3 --hashtype md5 --wordlist passwords.txt





