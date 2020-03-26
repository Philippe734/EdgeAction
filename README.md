# Edge Action for Linux

## Execute command when right clic on edge of screen for Linux

Use mouse gesture to take control of your Linux. You can set upto 4 commands. 

## Some examples

- You can close the active window with right clic on right edge of screen.
- You can open Firefox with a right clic on top edge of screen.
- You can do a backup of your data with a right clic on left edge of screen.
- You can run your own script with a right clic on top edge of screen.


![screenshot1 Linux](https://user-images.githubusercontent.com/24923693/77629873-7a662900-6f4a-11ea-92f4-e2f3aba0b428.png)
![screenshot1 Linux](https://user-images.githubusercontent.com/24923693/77629902-88b44500-6f4a-11ea-8152-a62c302d2ba2.png)
![screenshot1 Linux](https://user-images.githubusercontent.com/24923693/77629934-95389d80-6f4a-11ea-98a3-45362609f996.png)
![screenshot1 Linux](https://user-images.githubusercontent.com/24923693/77630089-cca74a00-6f4a-11ea-8d42-b6d662e70879.png)
![screenshot1 Linux](https://user-images.githubusercontent.com/24923693/77630117-d3ce5800-6f4a-11ea-854d-c9af85a279a8.png)


[![download][2]][1]

  [1]: https://github.com/Philippe734/EdgeAction/raw/master/Linux/1.0.12/edgeaction_1.0.12-0ubuntu1_all.deb
  [2]: https://cloud.githubusercontent.com/assets/24923693/21723900/7fdda69e-d432-11e6-8ab1-87dd79f36fe5.gif

## Install

Application written in Visual Basic Gambas, so you need to add the PPA for the Gambas language support:

1. Open terminal and add the PPA :
  ```
  sudo add-apt-repository ppa:gambas-team/gambas3 -y ; sudo apt-get update 
  ```
2. Download the package .deb and install it :
  ```
  sudo dpkg -i ~/Downloads/edgeaction_1.0.xxx.deb ; sudo apt-get install -fy
  ```
The dependancies for the Gambas language will be automatically installed.
- Or, here a one line to download and install it :
  ```
  sudo add-apt-repository ppa:gambas-team/gambas3 -y ; sudo apt-get update ; wget https://github.com/Philippe734/EdgeAction/raw/master/Linux/1.0.12/edgeaction_1.0.12-0ubuntu1_all.deb -P ~ ; sudo dpkg -i ~/edgeaction_1.0.12-0ubuntu1_all.deb ; sudo apt-get install -fy ; rm ~/edgeaction_1.0.12-0ubuntu1_all.deb
  ```
The application is not in the PPA and can't be install with a classic apt install :
  ```
  sudo apt install edgeaction # <<< don't work
  ```
## Profile

![youhou](https://cloud.githubusercontent.com/assets/24923693/21691776/43084e80-d37a-11e6-9571-5c6c60c19964.gif)

If you want to reward my work, or thank me, then you can [donate](http://vpnlifeguard.blogspot.fr/p/faire-un-don.html) a few dollars [HERE](http://vpnlifeguard.blogspot.fr/p/faire-un-don.html) and I'll be very happy!
