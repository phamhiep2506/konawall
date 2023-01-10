# konawall - Set wallpaper using feh

## Screenshot
![konawall](https://user-images.githubusercontent.com/64464369/211559815-6a511db6-3e82-4683-913c-e6bf202bc9e6.png)

## Image source
- [konachan.net](https://konachan.net) - (Safe)
- [konachan.com](https://konachan.com) - (Unsafe)

## Installation
```bash
git clone https://github.com/phamhiep2506/konawall
cd konachan
pip install -r requirements.txt
```

## Usage

`Current Python version 3.10.9`

```bash
usage: konawall [-h] [--random] [-d] [-w] [-m] [--setwall] [-id <INT>] [--list] [--unsafe]

Program set wallpaper using feh.

options:
  -h, --help  show this help message and exit
  --random    Random set wallpaper by day, week, month
  -d          Random popular images by day
  -w          Random popular images by week
  -m          Random popular images by month
  --setwall   Set wallpaper by id
  -id <INT>   ID image is number "350743"
  --list      Show list image by day, week, month
  --unsafe    Unsafe image source
```

### Available Modes
- `--random` - Random set wallpaper
- `--setwall` - Set wallpaper by id
- `--list` - Show list image by day, week, month
- `--unsafe` - Unsafe image source

### `--random` mode
Example:

- Random set wallpaper `-d`, `-w`, `-m` 
```bash
python konawall --random -d
```

### `--setwall` mode
- Set wallpaper `-id`
```bash
python konawall --setwall -id 350743
```

### `--list` mode
- Show list image `-d`, `-w`, `-m`
```bash
python konawall --list -d
```

### `--unsafe` mode
- Unsafe image source. Add the `--unsafe` flag to the end of the command line
```bash
python konawall --random -d --unsafe
```
