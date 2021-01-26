# ml-auto-app

# Demo

[Demo of this web app](https://share.streamlit.io/dataprofessor/ml-auto-app/main/app.py).

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *lazypredict*
```
conda create -n lazypredict python=3.7.9
```
Secondly, we will login to the *lazypredict* environement
```
conda activate lazypredict
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/ml-auto-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```

###  Launch the app

```
streamlit run app.py
```
