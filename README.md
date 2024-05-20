# cubes bot

Bot for Telegram [Cubes? game](https://t.me/cubesonthewater_bot?start=OTk3MTQzNDc5)

### Requirements:
1. Python 3+
2. Init params from WebView

### Usage:
1. `pip install requests`
2. `pip install colorama`
3. Create `init_data.txt` file and fill it with init data from game WebView (copy string from `window.Telegram.WebApp.initData` in DevTools console). You can enter multiple init data strings line by line for multithreading.

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


4. `python app.py`

You can also use proxy if create file `proxies.txt` (HTTP(s) only).