
# Local development version

First, clone the git repository, then checkout the master branch
(which is also the regular dev branch).

```
$ virtualenv -p `which python3` venv
$ sudo apt-get install `cat requirements-sys.txt`
$ . votes-venv/bin/activate
$ pip install -r requirements.txt
```
