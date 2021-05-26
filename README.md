# Zeplyn

Zeplyn allows to you **release python package fastly and easily** in one command so you can reiterate faster ```zeplyn publish```

## Installation

```
pip install zeplyn
```
## Usage

### zeplyn publish

In order to use ```zeplyn publish```, your folder will have to look like that :

```
├── Package Name
   ├── src (folder where there is the source code of your package)
        ├── main.py (file with the source code)
     
   ├── setup.py
   ├── README.md

```

Then you need to go to your Package Name directory with you command prompt ```cd Package Name``` and type ```zeplyn publish``` : it will ask you for your PyPi infos and then it'll upload it.


You should run that command in your command prompt in the folder directory where you want to put your package

Zeplyn also have a ```zeplyn create``` command which automatically create a readme file, a setup.py file and a src folder where your package's code is going to be stored.
