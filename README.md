

# myflask-setup

Make sure conda is installed (pip works too)

**Create a virtual environment**
```
   conda create -n [myenv] numpy
```
**Create env with specific package**
```
   conda create --name [myenv] python=3.5
   conda create -n [myflaskenv] flask
```
**Download common packages**
```
    # SQL Alchemy 
    conda install flask-sqlalchemy 
    
    # Flask Migrate
    pip install flask-migrate
    
    # Check list of packages
    conda list
```

**Activate virtual environment**
```
    source activate [myenv]
```

