# frontend
Web frontend for visualizing robot state.

## Installation (for development)


Install pip3,
```
sudo apt-get install python3-pip
```

Install virtual environments,
```
sudo apt-get install python3-venv
```

Create a venv named env,
```
python3 -m venv env
```

Activate your venv,
```
source env/bin/activate
```

First install `wheel`. 
```
pip3 install wheel
```

From this directory, install frontend. The `-e` flag makes the install editable so
if changes are made you do not need to uninstall then reinstall.

```
pip3 install -e .
```

Deactivate the venv,
```
deactivate
```

### Run

From the command line,

```
./run
```
