
<pre>
  _________  _____ __  __       ____       _ _     
 |__  / ___|| ____|  \/  |     | __ )  ___| | |___ 
   / /\___ \|  _| | |\/| |_____|  _ \ / _ \ | / __|
  / /_ ___) | |___| |  | |_____| |_) |  __/ | \__ \
 /____|____/|_____|_|  |_|     |____/ \___|_|_|___/
</pre>


Program for managing bells in my school

NOTE: Instructions for further maintainers are currently being work on...

<div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center;">
    <img src="https://i.imgur.com/CDXbbhS.jpg" alt="image" width="256" height="256" style="margin: 10px;">
    <img src="https://i.imgur.com/X4R9076.jpg" alt="image" width="256" height="256" style="margin: 10px;">
    <img src="https://i.imgur.com/FmvJAQ8.jpg" alt="image" width="256" height="256" style="margin: 10px;">
</div>

# Prerequisites (tested on) 📚
- Python >3.10.6
- Pip >22.0.2
- Git >2.34.1

# Setup ⚙️
0. Install venv  and python3 header files (if needed):
```
sudo apt install python3 python3-venv
```
```
sudo apt install python3-venv
```
```
sudo apt install python3-dev
```
1. Clone this repo:
```
git clone https://github.com/SmeggMann99/ZSEM-Bells.git/
```
2. Cd into the directory:
```
cd ./ZSEM-Bells
```
3. Clone my fork of the OPI.GPIO:
```
git clone https://github.com/SmeggMann99/OPI.GPIO.git/
```
3. Setup the virtual environment:
```
python3 -m venv venv
```
```
source ./venv/bin/activate
```
5. Build the OPI.GPIO module:
```
cd OPI.GPIO
```
```
sudo python3 setup.py install
```
```
pip install ./
```
6. Install required packages
```
pip install -r requirements.txt
```
7. Make the main file executable 
```
chmod +x ./main.py
```

# Running ⚡
### Option A:
1. Run the main script directly
```
./main.py &
```
### Option B:
1. Make a system service
... 
