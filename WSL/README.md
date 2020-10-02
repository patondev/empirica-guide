# Installation

* Please refer to this guide to install WSL2. https://docs.microsoft.com/en-us/windows/wsl/install-win10. Don't forget to turn on `Virtual Machine Platform` and `Windows Subsystem for Linux`. 

![Turn on feature](screenshots/1.png)

* After WSL installation is done, go to App Store, search for Ubuntu 20.04, and install it.

![Ubuntu Installation](screenshots/2.png)

* Then, you can launch terminal from there, do some setup.

![Setup](screenshots/3.png)

* Install NVM using script. Please refer to this guide: https://tecadmin.net/install-nodejs-with-nvm/

![NVM Installation](screenshots/4.png)

* Continue to meteor installation

![Meteor Installation](screenshots/5.png)

* After all installation are done and successful, as stated on https://empirica.ly/docs/quick-start.html. You can issue commands

```
npx create-empirica-app my-experiment
cd my-experiment
meteor
```

![Empirica is running](screenshots/6.png)

