# twilirok

Quickly bootstraps a local Twilio environment.

## Requirements

- Python 3
- ngrok
 
## Overview

A Python script that serves two functions:

1. Instantiates a new ngrok server
2. Updates the TwiML App with the new endpoint

## To use

1. Ensure the correct credentials are set in config.json
2. Install dependencies using
 
```shell
$ pip install -r requirements.txt
```

3. Run 

```shell
$ python twilirok.py
```

