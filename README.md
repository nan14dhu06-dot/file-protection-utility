
# File Protection Utility

## Overview
The File Protection Utility is a Python-based application used to secure files through encryption and restore them through decryption. This project demonstrates the concept of protecting sensitive data and controlled file access using cryptography techniques.

## Features
- Generate a secure encryption key
- Encrypt files into protected format
- Decrypt encrypted files back to original form
- Simple command-line interface
- Secure file handling using Fernet encryption

## Technologies Used
- Python
- Cryptography Library

## Installation

Install the required library:

```bash
pip install cryptography
```

## How to Run

Run the program using:

```bash
python "file python.py"
```

## Usage

### Generate Key
Choose option:

```text
1
```

This creates:

```text
secret.key
```

### Encrypt File
Choose option:

```text
2
```

Enter file name:

```text
sample.txt
```

Encrypted file created:

```text
sample.txt.encrypted
```

### Decrypt File
Choose option:

```text
3
```

Enter encrypted file name:

```text
sample.txt.encrypted
```

Decrypted file created:

```text
decrypted_sample.txt
```

## Project Structure

```text
file python.py
sample.txt
secret.key
sample.txt.encrypted
README.md
```

## Output
- Secure encrypted file generation
- Successful restoration of original file

## Author
Nandhitha V N 
