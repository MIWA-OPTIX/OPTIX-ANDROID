termux-setup-storage

pkg update && pkg upgrade -y

pkg install git python -y

pip install flask requests

git clone https://github.com/MIWA-OPTIX/OPTIX-ANDROID.git

cd OPTIX-ANDROID

python miwa.py
