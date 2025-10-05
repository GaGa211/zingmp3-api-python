# ZingMP3 API Python Client

> Unofficial Python client for ZingMP3 API
> **cre by TomDev211**

## ✨ Features

* Get chart home
* Search songs
* Get song info
* Get streaming URL
* Get lyric

## 📦 Requirements

* Python 3.8+
* [requests](https://pypi.org/project/requests/)

Install dependency:

```bash
pip install requests
```

## 🚀 Usage

Clone repo:

```bash
git clone [https://github.com/YOUR_USERNAME/zingmp3-api-python.git](https://github.com/GaGa211/zingmp3-api-python)
cd zingmp3-api-python
```

Hoặc import trong project khác:

```python
from zmp3 import chart_home, search_song, get_song, get_stream, get_lyric

# Chart home
print(chart_home())

# Search
print(search_song("Kẻ Thù - Ngọt", count=5))

# Song info
print(get_song("SONG_ID"))

# Streaming
print(get_stream("SONG_ID"))

# Lyric
print(get_lyric("SONG_ID"))
```

## 📄 License

MIT License — see [LICENSE](./LICENSE)
Author credit **must be retained** (`cre by TomDev211`).
