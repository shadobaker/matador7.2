# matador7.2
ا سلام خدمت دوستان عزیز 👌
مهدی رو هستم با آموزش نصب سورس اینلاین‌ ماتادور
میریم سر اموزش ... 
1⃣ فایل از حالت زیپ‌ خارج کرده و داخل سرور اپلود کنید.
======================
2⃣ سپس پیش نیاز ها سورس نصب میکنیم‌ ....
پیش نیاز ها در دو مرحله 👇
🔸 sudo apt-get update; sudo apt-get upgrade; sudo apt-get install tmux; sudo apt-get install luarocks; sudo apt-get install screen; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev; sudo apt-get update; sudo apt-get install; sudo apt-get install upstart-sysv

🔹 wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz;tar zxpf luarocks-2.2.2.tar.gz;cd luarocks-2.2.2 && ./configure; sudo make bootstrap;sudo luarocks install luasocket;sudo luarocks install luasec;sudo luarocks install redis-lua;sudo luarocks install lua-term;sudo luarocks install serpent;sudo luarocks install dkjson;sudo luarocks install lanes;sudo luarocks install Lua-cURL
======================
3⃣ وارد شماره‌ ربات میشیم‌ و  یه ربات (api) با @Botfather میسازیم اسم و ایدی وارد کرده (حالا باید اینلاین فعال کنید /setinline میزنیم و بعد ایدی بود رو میزنیم در اخر یه ok میفرسیم‌)
======================
4⃣ سپس‌ با شماره ربات ربات @userinfobot را استارت کرده و ایدی عددی شماره ربات را کپی کرده ...
======================
5⃣ وارد مسیر زیر میشیم 
MaTaDoR/api/bot/bot.lua
در خط [3] توکن ربات (api) که مرحله سوم با شماره ربات ساخیم وارد میکنید.
در خط [5] ایدی سودو اصلی یعنی خودتون قرار میدید
سپس در خط [30] ایدی عددی خودتان و ربات (cli) که در مرحله سوم گرفتیم قرار میدیم
سیو میکنیم‌ خارج میشیم‌ ....
======================
6⃣ وارد مسیر زیر میشیم‌
MaTaDoR/cli/plugins/MRCore
در خط [1] ایدی عددی سودو قرار میدهید .
سیو میکنم‌ خارج میشیم‌....
سپس وارد مسیر زیر میشویم 
MaTaDoR/cli/bot/bot.lua
و بعد در خط [19] ایدی ربات (api) را وارد میکنیم  توجه داشته باشید ایدی عددی ربات (api) اول توکن نوشته شده است
سیو میکنم‌ خارج میشیم‌....
======================
7⃣ دستورات زیر در ترمینال وارد کنید ...
▪️cd MaTaDoR/cli

▫️chmod +x matador.sh

▪️chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh

▫️./matador.sh install && ./matador.sh
======================
8⃣ صبر میکنیم تا کامل نصب شه وقتی با پیام زیر  مواجعه شدید
{Input Your Telegram ID :}
ایدی عددی سودو وارد میکنیم همون ایدی که در مرحله 6 در خط [1] قرار دادیم 
بعد اینتر میکنید
شماره ربات وارد مکنید کد میزنید‌
از سرور خارج و دوباره وصل میشید...
کد های زیر را در سرور میزنیم 
▪️cd MaTaDoR/api

▫️chmod +x matador.sh

▪️chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh

▫️./matador.sh install && ./matador.sh
از سرور خارج و دوباره وصل میشید...
======================
9⃣ دیگه اینجا ربات نصب شده حالا میخوایم روشن کنیم ...
کد زیر در سرور میزنید 
▪️killall screen

▫️cd MaTaDoR/cli

▪️tmux

▫️ screen ./auto.sh

اینجا ربات cli روشن شد از سرور خارج میشیم و دوباره وصل میشیم ...
کد های زیر میزنیم
▪️cd MaTaDoR/api

▫️tmux

▪️ screen ./auto.sh

توجه داشته باشید بعد از لانچ شده ربات (api) یا همون هلپر وارد شماره ربات میشم و ربات (api) که در مرحله سوم ساختیم /start میکنیم ...
======================
💢چند مورد راجب سورس میگن که سرعت در گروه های 5k سرعت پایینی داره ولی من لازم میدونم بگم بهتون که سورس با شماره ایران بزنید 😊 سرعتش خودتون میبینید =))


موفق باشید 😉
