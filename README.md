# Install Docker

docker run --rm -ti ophigeni/raw:xfce


# Install-Git

cd home

apt-get update

apt-get install git -y

git clone https://github.com/ophigeni/selenium-ophigeni


# Install-Selenium-and-Ect

wget -nc https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

apt update

apt install -f ./google-chrome-stable_current_amd64.deb -y

mkdir tests && cd tests

apt-get install python3-venv -y

python3 -m venv venv

source venv/bin/activate

pip install selenium webdriver-manager


# Copy File

cp /home/selenium-ophigeni/*.txt /home/tests/

cp /home/selenium-ophigeni/*.py /home/tests/

# Execute

bash 1.txt


# Tips

quit from ENV: deactivate



