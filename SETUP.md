```sh
brew install exiftool
python3 -m venv ./env
pip install -r requirements.txt
source ./env/bin/activate
```

```sh
./elodie.py import --debug --destination="/Users/micahmiller/Pictures/Backup" "/Users/micahmiller/Pictures/SCA_2"
```

Add file config.ini to ~/.elodie/config.ini 

```sh
cp config.ini ~/.elodie/config.ini
```

```
[Directory]
date=%Y-%m-%d
full_path=%date
```