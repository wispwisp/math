# math

## Jupyter enviroment

### virtualenv

```
apt install virtualenv
virtualenv venv
source ./venv/bin/activate
```

#### optional: specify version
`virtualenv -p python3.10 venv`

#### Exit virtualenv
`deactivate`

---

### dependencies

`pip install jupyter pandas numpy matplotlib seaborn scikit-learn`

---

### pip requirements
`pip install -r requirements.txt`

`pip freeze > requirements.txt`

### start jupter

`jupyter notebook --ip=0.0.0.0 --port=8888`

`--ip=0.0.0.0` - from vbox
