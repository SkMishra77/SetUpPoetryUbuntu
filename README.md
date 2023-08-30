# SetUpPoetryUbuntu
To install Poetry on Ubuntu and add it to your system's path, you can follow these steps:
# Install Poetry:
Open a terminal and execute the following command to install Poetry using the curl command:
```bash
curl -sSL https://install.python-poetry.org | python3 -
```

## Add Poetry to PATH:

After installing Poetry, you need to add its executable path to your system's PATH so that you can run it from any directory.

```bash
nano ~/.bashrc
```

```py
export PATH="$HOME/.poetry/bin:$PATH"
or 
export PATH="/home/ubuntu/.local/bin:$PATH"
for Ubuntu
```

save the file using 
```Ctrl + x + y + Enter```
## Reload the Shell Configuration:

```bash
source ~/.bashrc
```

## Check Version
```bash 
poetry --version
```
