As with any django project, you need to create a virtual environment for your project so that everything you install for this project will not affect anything outside and vice versa.



I'll just go through the steps real quick:

1. Create a virtual environemnt.
2. Go into the virtual environment.
3. Activate the virtual environemnt.

In this case, I'm naming the virtual environment `env`, but you can call it anything you want.

**Mac**:
```shell
$ python3 -m venv env
$ cd env
$ source bin/activate
```

**Windows**:
```shell
$ virtualenv env
$ cd env/Scripts
$ activate
```

Notice after activating the virtual environement, the environment's name is shown in brackets on the left hand side.

So make sure anytime you're working on the project the virtual environment is activated (name is shown in brackets on the left hand side).
