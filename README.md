# ansible-dots

## What is this?
This is an ansible project to configure my workstations. This project utilizes ansible-pull method. I manage my installed packages and [dotfiles](https://github.com/NafiAsib/dotfiles) through this project. This is by no means a standard ansible project with best practices. My goal is to configure my working environment in a fresh install as fast as possible, that's all.

### How to use
***You should not use this directly, rather look up my tasks and create one for your own purpose***
```bash
$ sudo apt install ansible
$ ansible-pull -U https://github.com/NafiAsib/ansible-dots.git --ask-become-pass
```
***dont't use `sudo ansible-pull`, otherwise you're always root user unless specified!***

![image](https://user-images.githubusercontent.com/38901581/127496564-7360f7cb-5130-427f-96e0-d58602ea2e98.png)

### TODO
* Packages
- ~[ ] [exa](https://the.exa.website/install/linux#manual) ***might not need manual installation after 22.04 lTS***~
- [ ] [nvm](https://github.com/nvm-sh/nvm)
- [ ] docker
- [ ] docker compose
- [ ] `hosts` file
- [ ] study more about `ansible`
- [ ] better log
- [ ] Better macOS compatability

## Resources

- [My explanation of Ansible Pull](https://notes.nafiasib.com/cloud-computing/ansible) - I wrote it nearly 3 years ago, so it might be outdated!
- [Using Ansible "Pull" Mode to Dynamically Automate Server/Workstation Builds - Learn Linux TV](https://www.youtube.com/watch?v=sn1HQq_GFNE)
- [dotfiles - ALT-F4-LLC](https://github.com/ALT-F4-LLC/dotfiles)
- [dotfiles - techdufus](https://github.com/techdufus/dotfiles)
