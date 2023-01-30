# Module-18-Blockchain
Pychain

As a fintech engineer, my task in this assignment is to build a blockchain-based ledger system  with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

## Step 1- Import following libraries
.import streamlit as st
.from dataclasses import dataclass
.from typing import Any, List
.import datetime as datetime
.import pandas as pd
.import hashlib

## Step 2- Create a Block @dataclass including a hash_block method with following attributes
Record, creator_id, prev_hash, timestamp, nonce.

## Step 3- Create Pychain @dataclass with chain attribute including proof_of_work, add_block and is_valid functions
chain attribute takes List[Block]

## Step 4- Streamlit/ Test the PyChain Ledger by Storing Records



