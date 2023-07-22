# pychain

This project involves developing a blockchain-based ledger system, named PyChain, with a user-friendly web interface. This ledger allows partner firms to conduct, record, and verify transactions with one another. The PyChain ledger uses proof-of-work algorithms to validate new blocks and hash functions to secure the contents of these blocks within the chain.

## Technologies

This project uses Python programming language and the Streamlit library to create the user-friendly web interface. Additionally, it uses the dataclasses, typing, datetime, pandas, and hashlib libraries.

## Installation and Usage

You will need to install Streamlit using pip:

```bash
pip install streamlit
```

To run the application:

```bash
streamlit run pychain.py
```

## Steps

1. Create a Record Data Class: A new data class named Record was created to serve as the blueprint for the financial transaction records that the blocks of the ledger will store.

2. Modify the Existing Block Data Class to Store Record Data: The existing Block data class was modified by replacing the generic data attribute with a record attribute that’s of type Record.

3. Add Relevant User Inputs to the Streamlit Interface: Additional user input areas were created in the Streamlit application. These input areas collect the relevant information for each financial record that you’ll store in the PyChain ledger.

4. Test the PyChain Ledger by Storing Records: The complete PyChain ledger and user interface was tested by running the Streamlit application and storing some mined blocks in the PyChain ledger. The blockchain validation process was also tested by using the PyChain ledger.

## Project Status

The current project successfully creates and displays a blockchain ledger, though there are some issues with the user input fields. Further debugging and testing are required to ensure it is functioning as expected.

## Contributors

James White
