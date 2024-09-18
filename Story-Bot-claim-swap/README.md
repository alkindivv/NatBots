# claim faucet and swap tokens into IP tokens.

## Prerequisites

- Python 3.x
- `pip` (Python package installer)

## Setup Instructions

**1. Create a Virtual Environment.**

To isolate the project dependencies, create a virtual environment:

```bash
python -m venv venv
```

### 2. Activate the Virtual Environment
- for windows
```bash
venv\Scripts\activate
```

- for macOS/Linux
```bash
source venv/bin/activate
```

### 3. Install Requirements
```bash
pip install -r requirements.txt
```

### 4. Usage
- run script to claim faucet
```bash
python faucet_bot.py
```

- run script to swap faucet token into IP
```bash
python swap_to_ip.py
```

## Warning

- Ensure you have sufficient IP balance for gas fees.
- Never share your private keys.
- Use this bot at your own risk.

## Contributing

Contributions are always welcome. Please make a pull request or open an issue for suggestions and improvements.

## License

[MIT](https://choosealicense.com/licenses/mit/)
