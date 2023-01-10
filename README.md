# Konachan.net - Wallpaper
- [konachan.net](https://konachan.net) - (Safe)
- [konachan.com](https://konachan.com) - (Explicit)

![preview.gif](./preview.gif)

## Video demo
[![Video demo](https://img.youtube.com/vi/LofcX9y7lb0/0.jpg)](https://www.youtube.com/watch?v=LofcX9y7lb0)

## Installation
```bash
git clone https://github.com/phamhiep2506/konawall
cd konachan
pip install -r requirements.txt
```

## Run
```bash
python konawall
```

## Configure image source url
- Edit file [konachan](./konawall)
- Safe source images (Safe)
```python
KONACHAN_URL = "https://konachan.net"
```

- Explicit source image (Unsafe)
```python
KONACHAN_URL = "https://konachan.com"
```
