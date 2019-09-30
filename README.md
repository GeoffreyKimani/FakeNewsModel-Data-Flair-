# Fake News Classifier #

Many users end up in a filter bubble on online media platforms with all sorts of news roaming the space. This project uses TfidfVectorizer and Passive Aggressive Classifier to detect fake news.

## Setting Up The Project. ##

### Install from github repo. ###
```git clone https://github.com/jeffkim207/FakeNewsModel-Data-Flair-.git```

###Check for python in your system. ###

Python and pip are required. Check if they are installed by running;
```
sudo python --version
sudo pip --version

```

If not this can be resolved by running;
```
sudo apt-getupdate
sudo apt-get -y install python3python-pip python-dev

```

### Jupyter NoteBook ###

If you don't have jupyter notebook follow the steps below to install 
```
sudo -H pip install jupyter
```

Start your notebook by writing this command: 
```sudo jupyter notebook```

Any errors of root access can be resolved by:
```sudo jupyter notebook --allow-root```

### Running the notebook ###

Run the following command to install required libraries:
```sudo pip install numpy pandas sklearn```

If you are using a virtual environmnent you can create a kernel by running the following command:
```ipython kernel install --user --name <<name_of_venv>> --display-name="<<name to display in jupyter kernel>>"```

