# Description
SPKI Pin Hash - Generates SPKI pin hashes from X.509 PEM files. 
This tool is a Python3 implementation of Moxie's tool: https://github.com/moxie0/AndroidPinning/blob/master/tools/pin.py

A pin is a hex-encoded hash of a X.509 certificate's SubjectPublicKeyInfo. A pin can be generated using the provided script.

# Installation & Usage
```
git clone https://github.com/ViktorMares/SPKI_pin_hash.git
```
```
cd SPKI_pin_hash
```
```
pip3 install requirements.txt
```
```
python3 pin3.py cert_file
```

# Sample Output:
![pin3_py](https://github.com/ViktorMares/SPKI_pin_hash/assets/80492489/fd7ffe9a-9bd1-4424-bdf4-2c0af8b1738b)
