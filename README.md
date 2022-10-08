# 🐝 Beencrypted
 
If you want to encrypt your strings and want to have the Bee Movie script in your code, then this is the Python package for you!
With this package, you can encrypt strings to the first part of the Bee Movie script and decrypt it back.

▶️ This project is still under development and obviously don't use this as your secure encryption

### Examples

##### Encryption
```python
from beencrypt

string = "Barry B Benson"
print(beencrypt.encrypt(string))
```

##### Decryption
```python
from beencrypt

string = "ToAccordingItsItsLittleCareToCareToLawsShouldWingsBeShould"
print(beencrypt.decrypt(string))
```
### Characters

Beencryption only supports the Latin alphabet, numbers and some basic symbols. Decrypted strings will not have capitals. Letters or symbols that are not supported will have been replaced with "Barry" in the encrypted string and will be lost in decryption.

```abcdefghijklmnopqrstuvwxyz1234567890 .,-:;/?!```

###### PyPi
You can go to [PyPi](https://pypi.org/project/beencrypted/) to install it.
