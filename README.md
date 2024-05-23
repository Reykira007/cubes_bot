# cubes bot

Bot for Telegram [Cubes? game](https://t.me/cubesonthewater_bot?start=OTk3MTQzNDc5)

### Requirements:
1. Python 3+
2. Init params from WebView

### Usage:
1. ```bash
     pip install requests
   ```
2. ```bash
     pip install colorama
   ```
3. Create `init_data.txt` file and fill it with init data from game WebView (copy string from `window.Telegram.WebApp.initData` in DevTools console). You can enter multiple init data strings line by line for multithreading.

``Step init_data.txt``
1. open desktop telegram and open the cube? game then click start
2. ```bash
     CTRL + SHIFT + I
   ```
3. ```bash
     window.Telegram.WebApp.initData;
   ```
   ![image](https://github.com/Reykira007/cubes_bot/assets/70166715/b2fabe48-8126-4af7-8fd1-e7071deddb76)

4. copy query_id
   ![image](https://github.com/Reykira007/cubes_bot/assets/70166715/7f328950-4732-493a-9619-c94d0f75a79c)






4. ```bash
     py app.py
   ```
   ![image](https://github.com/Reykira007/cubes_bot/assets/70166715/546911cb-8677-4391-9954-8a4f04d70b1a)


You can also use proxy if create file `proxies.txt` (HTTP(s) only).
