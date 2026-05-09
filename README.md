termux-setup-storage
pkg update && pkg upgrade -y
pkg install git python -y
pip install flask requests
git clone https://github.com/MIWA/MIWA-PREMIUM.git
cd MIWA-PREMIUM
python start_miwa.py
