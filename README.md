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
1. open telegram dekstop
2. ```bash
     CTRL + I
   ```
3. ```bash
     window.Telegram.WebApp;
   ```
   ![image](https://github.com/Reykira007/cubes_bot/assets/70166715/c3a2afe4-ac06-46fc-a4ac-bf73fbbb1d04)
5. klik kanan copy object

   ![image](https://github.com/Reykira007/cubes_bot/assets/70166715/cfd3bd32-4f2d-42b3-a8ec-70975e6001d3)
7. paste di file ``init_data.txt``
   ![image](https://github.com/Reykira007/cubes_bot/assets/70166715/9a68f203-e9d1-4e2d-a836-2118265d449f)
8. hapus yang lain sisakan query_id
   ![image](https://github.com/Reykira007/cubes_bot/assets/70166715/7f328950-4732-493a-9619-c94d0f75a79c)






4. ```bash
     py app.py
   ```

You can also use proxy if create file `proxies.txt` (HTTP(s) only).
