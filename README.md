# ter-m-aven

Maven for termux 

## Installation

Type the following into termux

```
wget https://github.com/suhan-paradkar/ter-m-aven/releases/download/v3.8.1/install.sh 
bash install.sh
```

## Build yourself

```
pkg install termux-create-package git
git clone https://github.com/suhan-paradkar/ter-m-aven
cd ter-m-maven
termux-create-package manifest.json
```
