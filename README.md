# VeracodeELK
Application to transform Veracode reports to ingest in Elastic Search

# Prerequisites
You need create and configure a Veracode API credentials file in your environment

Configure a Veracode API credentials file on Windows:
https://help.veracode.com/r/t_configure_credentials_windows?tocId=Qkz0SDLqDEHDj59OKUj5aw

Configure a Veracode API credentials file on MacOs or Linux:
https://help.veracode.com/r/t_configure_credentials_mac?tocId=blvs025_41S686OrCXMkdQ

Configure a Veracode API credentials as Environments Variables on MacOS and Linux
https://help.veracode.com/r/t_store_creds_linux_env

# Install

git clone https://github.com/sun022-01/VeracodeELK.git

cd VeracodeELK

pip install -r requirements.txt

# Use

python VeracodeELK.py --config utils/config.yml --output json


# Project based on "veracode-to-splunk" by andreyglauzer
https://github.com/andreyglauzer/veracode-to-splunk