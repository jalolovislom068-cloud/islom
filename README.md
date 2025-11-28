# islom
islom
music_search_bot/
 ├── bot.py               # Asosiy ishga tushirish fayli
 ├── config.py            # API token, sozlamalar
 ├── db.py                # SQLite3 bilan ishlash
 ├── audio/               # Yuklangan MP3 fayllar
 ├── handlers/            # Routerlar va handlerlar
 │     ├── start.py
 │     ├── search.py
 │     ├── trends.py
 │     ├── favorites.py
 ├── keyboards/           # Tugmalar va menyular
 │     ├── menu.py
 ├── states/              # FSM holatlari
 │     ├── search_state.py
 └── utils/               # Qo‘shimcha funksiyalar
       ├── downloader.py  # MP3 yuklash va konvertatsiya
