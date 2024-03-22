```markdown
# Bitcoin-Wallet
## 3 Easy Steps to Create a Bitcoin Wallet in Python

### Step 1: Install Library
To create a Bitcoin wallet in Python, you first need to install the `bitcoinaddress` library. You can do this using PIP in your actual or virtual environment. Here are three common ways to install the library:

- For Python 3:
  ```
  pip3 install bitcoinaddress
  ```

- For Standard Python and Python 2 Installation:
  ```
  pip install bitcoinaddress
  ```

- For Jupyter Notebook Cell:
  ```
  !pip install bitcoinaddress
  ```

### Step 2: Import and Create Wallet
Once the library is installed, you can import the `Wallet` class from the `bitcoinaddress` module. This class allows you to easily create a new and random public/private keypair using the `Wallet()` constructor method.

```python
from bitcoinaddress import Wallet
wallet = Wallet()
```

### Step 3: Print Wallet
Now that you have created a wallet, you can print its content to view the public and private keys along with the addresses associated with them.

```python
print(wallet)
```

Follow these three simple steps to create your own Bitcoin wallet in Python.
```
