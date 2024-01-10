# Padding Oracle Attack

## Overview

This project demonstrates a Padding Oracle Attack to decipher an encrypted message using the Data Encryption Standard (DES) algorithm in Cipher Block Chaining (CBC) mode. The attack takes advantage of a vulnerability in the padding scheme to reveal the original plaintext without knowledge of the secret key.

## Files

- **padding_oracle_attack.py**: Python script implementing the padding oracle attack.
  
## Dependencies

- [Cryptodome](https://www.pycryptodome.org/): A self-contained Python package of low-level cryptographic primitives.

## Usage

1. Ensure that you have Python installed on your system.
2. Install the required dependencies: `pip install pycryptodome`
3. Execute the script with the following command:

   python padding_oracle_attack.py [initialization_vector] [key] [ciphertext]
   
Replace [initialization_vector] ,[ciphertext] with the appropriate hexadecimal values and [key] with a string value
## Example

```python  
python padding_oracle_attack.py 646c33c9265da327f44d3a891131c816 Aalesund f2b2544ff59d2773

running this commend should result in the output:

## Disclaimer
This project is for educational purposes only. Unauthorized use of these techniques may violate applicable laws and regulations.
