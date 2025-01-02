# Install Docker

docker run --rm -ti ophigeni/raw:xfce

docker run --rm -ti ophigeni/raw:mate


# Install-Git

cd home

apt-get update

apt install nano -y

apt-get install git -y

git clone https://github.com/ophigeni/docker-raw-selenium


# Install-Selenium-and-Ect

apt install wget

wget -nc https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

apt update

apt install -f ./google-chrome-stable_current_amd64.deb -y

mkdir tests && cd tests

apt-get install python3-venv -y

python3 -m venv venv

source venv/bin/activate

pip install selenium webdriver-manager


# Copy File

cp /home/docker-raw-selenium/*.txt /home/tests/

cp /home/docker-raw-selenium/*.py /home/tests/

# Execute

bash 1.txt


# Tips

edit file text with: nano 1.py

quit from ENV: deactivate



