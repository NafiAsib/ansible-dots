# ansible-dots

## What is this?
This is an ansible project to configure my workstations. This project utilizes ansible-pull method. I manage my installed packages and [dotfiles](https://github.com/NafiAsib/dotfiles) through this project. This is by no means an standard ansible project with best practices. My goal is to configure my working environment in a fresh install as fast as possible, that's all.

### How to use
***You should not use this directly, rather look up my tasks and create one for your own purpose***
```bash
$ sudo apt install ansible # if ansible is not installed
$ ansible-pull -U https://github.com/NafiAsib/ansible-dots.git --ask-become-pass
$ # sudo ansible-pull -U https://github.com/NafiAsib/ansible-dots.git
$ # with sudo, you're always root unless specified
```
![image](https://user-images.githubusercontent.com/38901581/127496564-7360f7cb-5130-427f-96e0-d58602ea2e98.png)

### TODO
* Packages
- [ ] exa
