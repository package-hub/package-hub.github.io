---
title: High-Frequency-Trading-Model-with-IB
categories: ['python']
---
## [High-Frequency-Trading-Model-with-IB](https://github.com/jamesmawm/High-Frequency-Trading-Model-with-IB)

### A high-frequency trading model using Interactive Brokers API with pairs and mean-reversion in Python


Steps to run the trading model on your command line:

- Within a Python 3.7 environment, install the requirements:
    
        pip install -r requirements.txt

- In IB Trader Workstation (TWS), go to **Configuration** > **Api** > **Settings** and:

    - enable ActiveX and Socket Clients
    - check the port number you will be using
    - If using Docker, uncheck **Allow connections from localhost only** and enter the machine IP running this model to **Trusted IPs**.

- Update `main.py` with the required parameters and run the model with the command:

        python main.py
    