
# Raning_Py

Raning_Py is CLI wearther app created with python based on this [Real Python](https://realpython.com/build-a-python-weather-app-cli)
tutorial 


## Screenshot

![App Screenshot](https://github.com/akshayCODE27/blob_files/blob/main/raining_py/screenshots/Screenshot.png?raw=true)


## Requirements
To run this CLI app, you need a modern installation of Python >= 3.6.

You also need an API key for OpenWeather's API. After signing up and generating your API key,

## Run Locally

Clone the project

```bash
  git clone https://github.com/akshayCODE27/raining_python
```

Go to the project directory

```bash
  cd my-project
```
add your own API key from [OpenWeather](https://home.openweathermap.org/api_keys) 
create a  ```secrets.ini ``` file
add the API key to the secrets.ini config file:
```python
[openweathermap]
api_key = <YOUR-OPENWEATHERAPP-API-KEY>
```
Go to the project directory

```bash
  python <city name>
```
example:

```bash
  python New Delhi
```

for impirial units

```bash
  python <city name> -i
```

