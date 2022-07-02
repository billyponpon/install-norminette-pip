# install-norminette-pip
How to install norminette and pip inside mac

1. Check your python version
https://ehmatthes.github.io/pcc/chapter_01/osx_setup.html#:~:text=Checking%20your%20current%20version%20of%20Python,-Python%20is%20probably&text=To%20check%20if%20it's%20installed,%2C%20and%20then%20press%20Enter.)&text=If%20you%20have%20Python%203.4,by%20using%20the%20installed%20version.

2. Make sure you have latest pip
https://www.groovypost.com/howto/install-pip-on-a-mac/#:~:text=To%20use%20the%20get%2Dpip,pip.py%20and%20press%20Enter.

3. Install from https://github.com/42School/norminette
python3 -m pip install --upgrade pip setuptools
python3 -m pip install norminette

upgrade with
python3 -m pip install --upgrade norminette

4. Add your install path into command so your mac knows it can use it
https://www.architectryan.com/2012/10/02/add-to-the-path-on-mac-os-x-mountain-lion/
sudo nano /etc/paths
add your installed path inside it Ctr O and Ctr X

Done.
