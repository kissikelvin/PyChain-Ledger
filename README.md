# PyChain-Ledger

![Display](Resources/Blockchain.png)

# Overview

In this repository I used [Streamlit](https://streamlit.io/) for the web interface in order to build a blockchain-based ledger system.

This ledger should enable individuals to perform financial transactions, such as transferring money between senders and receivers, and to ensure the integrity of the data within it.

# Objectives

* Create a new data class named **`Record`**.
* Modify the existing **`Block`** data class to store **`Record`** data.
* Add Relevant User Inputs to the **`Streamlit`** interface.
* Test the PyChain Ledger by Storing **`Records`**.

## Installation

Before running the application, import the following libraries:

````
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib
````


# Step 1: Created a **`Record`** Data Class

![Display](Resources/dataclass.png)


# Step 2: Modified the Existing Block Data Class to Store **`Record`** Data

![Display](Resources/Blockmodification.png)


# Step 3: Added Relevant User Inputs to the **`Streamlit`** interface.

![Display](Resources/userinputs.png)

# Step 4: Tested the PyChain Ledger by Storing **`Records`**.

The images below showcase the Streamlit UI interface displaying the results after storing transactions and validating records in the PyChain Ledger. Key details, including "Sender," "Receiver," "Amount," "Block," "Creator ID," and "Previous Hash," are provided for reference.

# Transaction Record Stored in PyChain 

![Display](Resources/Addingnewblock.png)

# Blockchain Validation Process

![Display](Resources/BlockchainvalidationPychain.png)

---

<div align="center">
   
   [Source Code](https://github.com/kelvinkissi/PyChain-Ledger/blob/main/pychain.py)
   
</div>

---
