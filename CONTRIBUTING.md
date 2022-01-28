# DSM Exposed Contributing Guide

As an open source project, contributions are welcome. Please review this document to get up and running locally.


## Requirements

- python3.9+

## Setup


### Create and Activate Virtual Environment

```zsh
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### Using data.iowa.gov

> You'll need to get your own socrata API key and secret

see https://github.com/xmunoz/sodapy


Copy the example config file `cp config/config_example.json config/config.json`


Add secrets to `config/config.json`


### Datasets

https://dev.socrata.com/foundry/data.iowa.gov/smfg-ds7h