# create virtual environment
python -m venv venv

# for windows
venv\Scripts\activate # for windows

# for macOS/Linux
source venv/bin/activate

# install requirements
pip install -r requirements.txt

# run scipts for claiming faucet
python faucet_bot.py

# run scipts for swap faucet into IP token
python swap_to_ip.py
