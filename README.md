# 🦉 PyAnime4Up
> This Is A Selenium-less Python Library That Allows You To Interact With Anime4Up

## ⚙ Installation :
[![Total Downloads](https://static.pepy.tech/personalized-badge/pyanime4up?period=total&units=none&left_color=black&right_color=blue&left_text=Total-Downloads)](https://pepy.tech/project/pyanime4up)

You Can Simply Install The Library From PyPI With This Command:
```bash
pip3 install PyAnime4Up
```

## ❓ Usage :
#### Search :
```python
from PyAnime import Anime

result = Anime().search("death")
print(result)

```

#### Get Anime Info :
```python
from PyAnime import Show

title = Show("https://anime4up.art/anime/death-note/").title()
print(title)

info = Show("https://anime4up.art/anime/death-note/").info()
print(info)

category = Show("https://anime4up.art/anime/death-note/").category()
print(category)

story = Show("https://anime4up.art/anime/death-note/").story()
print(story)

image = Show("https://anime4up.art/anime/death-note/").image()
print(image)

trailer = Show("https://anime4up.art/anime/death-note/").trailer()
print(trailer)

```

#### Get Episode Link / Num:
```python
from PyAnime import GetEpisodes

all_eps = GetEpisodes("https://anime4up.art/anime/death-note/").all_eps()
print(all_eps)

```

#### Get Download Links :
```python
from PyAnime import Episode

dl_links = Episode("https://anime4up.art/episode/death-note-%d8%a7%d9%84%d8%ad%d9%84%d9%82%d8%a9-37-wxpbu/").dl_links()
print(dl_links)

```

## 🪐 Credits:
* [DamienSoukara](https://github.com/AmineSoukara) For [Nothing](https://github.com/AmineSoukara/PyAnime4Up)
