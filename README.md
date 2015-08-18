FoxBox
===========

Version: 0.7

FoxBox project's goal is to try any approach that make new user can do as less as possible to start the FirefoxOS development. Currently foxbox take about one hour to auto setup (depends on net speed) a Firefox OS (Gaia) build environment in VM.

## Features

- Setup environment and required libraries automatically
- Compile in VM, flash to device directly
- Edit source code in your host machine with any editor and have the files sync into the guest machine.

## How to Run

Prepare:

[Download](http://github.com/gasolin/foxbox/releases) or Clone http://github.com/gasolin/foxbox.git via `git clone` command to local computer (we call it Host OS). Then enter the foxbox folder and type commands:

```
$ git clone https://github.com/gasolin/foxbox.git
$ cd foxbox
$ ./configure.sh
```

Follow instructions on screen to specify internet connection and the root permission password. Now the environment is settled for you. (the default vagrant box username/password is `vagrant/vagrant`)

Inside of virtualbox, run command:

    $ gaia_init.sh

to clone gaia source code. Or you could use normal way to git clone [gaia](https://github.com/mozilla-b2g/gaia).


If you need more support, read [wiki](https://github.com/gasolin/foxbox/wiki) for more instructions.

## Community

* [Google+ forum](https://plus.google.com/communities/109304362439467302985)
* [Issue list](https://github.com/gasolin/foxbox/issues?state=open)

## Credit

Foxbox is based on the [gist](http://gist.github.com/yzen/7723421) by Yura Zenevich.

## License

FoxBox follow [MPL](http://www.mozilla.org/MPL/) 2.0 License.
