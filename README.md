Discord Username Checker
I have reverted the update for the checker, and made some adjustments. It will now go back to needing the Change Name Update option available for it to work!

image

Changelog
Added Proxy Support
Can now use username text files
Join Discord for any updates planned
On the lookout to find rare, or unique usernames? This username checker can generate random usernames and check them to see if they are avaliable!

You can use this to find any possible 2 letter usernames

Authors
@ClientlessX
WARNING
Spamming Discords API is against TOS and can lead to your account being suspended or banned, please use an alt when doing this! I am not responsible for any damage casued by the end user

Usage/Examples
REQUEST_HEADERS = {
    "Content-Type": "Application/json",
    "Orgin": "https://discord.com/",
    "Authorization":"TOKEN-HERE"
}
You need to make sure you put your token in or you will not have access to check for usernames

For Windows

pip install -r requirments.txt
python username_checker.py
For linux

git clone https://github.com/clientlessx/Discord-Username-Checker.git
pip3 install -r requirments.txt
python3 username_checker.py
Support
