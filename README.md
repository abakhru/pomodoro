## Simple Pomodoro MacOS app using rumps

- Build the env
```
python3 -m poetry install
```

- Build the app using following command
```
python3 setup.py py2app
```

- yapf integration
```
# From the root of your git project.
curl -o pre-commit.sh https://raw.githubusercontent.com/google/yapf/master/plugins/pre-commit.sh
chmod a+x pre-commit.sh
mv pre-commit.sh .git/hooks/pre-commit
```
- running yapf:
```
yapf -i -r -vv -p *.py
```

#### Reference:
- https://camillovisini.com/create-macos-menu-bar-app-pomodoro/
