# DevLand 

This is the reference implementation of the DevLand application. If you are interested in helping out, please do not hesitate to do so. We have a lot of features that have yet to be programmed and created within the application itself, check the issues and get to coding if you are interested in contributing. 

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ cd ~/tmp
$ mkdir devland
$ cd devland
$ git clone https://github.com/m-henderson/DevLand.git
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

On Cloud9, this command should be

```
$ rails server -b $IP -p $PORT
```

instead.


You can find the branch name using

```
$ git branch -a
```

if you need to drop tables, re-migrate, and re-seed. 

```
$ rails db:reset
```
