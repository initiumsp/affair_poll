# Affair Opinion Poll

## Introduction
This is a poll of users' opinions of having affairs.
Initiated by the Hong Kong News group of Initium Media, implemented by Initium Lab engineer Andy Shu.

## Dependencies

### Preparation

You need to install [NodeJS](https://nodejs.org/).

Then use npm to install grunt commandline tools:
```
npm install -g grunt-cli
```
You might have to sudo.

Then, in the root project directory, run this to install all JavaScript packages:
```
npm install
```

### Virtual Environemnt for Development
Install the virtualisation suite:

- VirtualBox
- Vagrant

Download image and launch virtual machine:

```
vagrant box add ubuntu/trusty64
vagrant up
```

Login the virtual machine and run server:

```
vagrant ssh
cd /vagrant
grunt serve
```

Then visit
<http://localhost:9000/>

If you prefer not to use Vagrant for a unified environment, you can try to run
```
grunt serve
```
in the root directory. Then visit
<http://localhost:9000/>
