# Edge Action for Linux

## Execute command when right clic on edge of screen for Linux

You can set upto 4 commands. Enclose a command with " before and after. For a script, enclose the path with " and ' before and after. Use # before to comment it.


![screenshot1 Linux](https://user-images.githubusercontent.com/24923693/77629873-7a662900-6f4a-11ea-92f4-e2f3aba0b428.png)



## Install

Application written in Visual Basic Gambas, so you need to add the PPA for the Gambas language support:

1. Open terminal and add the PPA :
  ```
  sudo add-apt-repository ppa:gambas-team/gambas3 -y ; sudo apt-get update 
  ```
2. Download the package .deb and install it :
  ```
  sudo dpkg -i ~/Downloads/edgeaction_1.0.11-0ubuntu1_all.deb ; sudo apt-get install -fy
  ```
The dependancies for the Gambas language will be automatically installed.
The application is not in the PPA and can't be install with a classic apt install :
  ```
  sudo apt install edgeaction # <<< don't work
  ```
## Profile

![youhou](https://cloud.githubusercontent.com/assets/24923693/21691776/43084e80-d37a-11e6-9571-5c6c60c19964.gif)

If you want to reward my work, or thank me, then you can [donate](http://vpnlifeguard.blogspot.fr/p/faire-un-don.html) a few dollars [HERE](http://vpnlifeguard.blogspot.fr/p/faire-un-don.html) and I'll be very happy!

[![download][2]][1]

  [1]: https://github.com/Philippe734/EdgeAction/raw/master/Linux/1.0.11/edgeaction_1.0.11-0ubuntu1_all.deb
  [2]: https://cloud.githubusercontent.com/assets/24923693/21723900/7fdda69e-d432-11e6-8ab1-87dd79f36fe5.gif
