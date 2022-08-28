# Fast-Boot
Tired of re-installing all packages of ubuntu thousands of times, here I try to provide some requirements and commands to accelerate the re-installing process

## apt install
sed 's/#.*//' requirement-file.txt | xargs sudo apt-get install -y


## pip - requirements.txt
pip install -r requirements.txt
