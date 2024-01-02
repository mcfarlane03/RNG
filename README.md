# Internet of Things (IoT) Template


# Hardware Setup
Download and install [Arduino](https://www.arduino.cc/en/software) IDE. Subsequently, install the following Arduino IDE libraries:
1. Adafruit GFX Library by Adafruit
2. Adafruit ILI9341 by Adafruit
3. ArduinoJson by Benoît Blanchon
4. PubSubClient by Nick O’Leary

# Backend Setup

Always ensure to establish a virtual environment and install the necessary packages from your requirements file if you haven't already done so. Following that, activate your virtual environment and proceed to run your Flask API.

###Create a virtual environment - env

Windows 
```sh
python -m venv env  
```
Linux
```sh
python3 -m venv env  
```
Activate env
```sh
.\env\Scripts\activate (or source env/bin/activate on linux) 
```
Install API requirements
```sh
pip install -r requirements.txt 
```
Start Flask API
```sh
py run.py (or python run.py on linux)
```


```bash
$ python -m venv env (you may need to use python3 instead)
$ source venv/bin/activate (or .\venv\Scripts\activate on Windows)
$ pip install -r requirements.txt 
$ python run.py
```


### Start Flask API

# Frontend Setup

## Recommended IDE Setup
[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
