# RuTracker.org parser on python
Search and download torrents from popular tracker http://rutracker.org

## Installing
Before running the script, you must install the packages following items:
```
$ pip install grab
$ pip install colored
```

## Usage
```
./rutracker.py SEARCH_QUERY
```
Note that you might need to give executable permissions to the file or you can just run:

```
python rutracker.py SEARCH_QUERY
```
Optional args:
* --count view max result
* --no-download only search torrents
* --no-run-torrent dowload without run client-torrent

## Examples
* Search for three films "I am Legend" and download the torrent file without starting:
``` bash
$ python rutracker.py "I am legend" --no-run-torrent -c 3
Username: <LOGIN>
Password: *****
ID: 1
Title: Я - легенда / I Am Legend (Френсис Лоуренс / Francis Lawrence) [2007, фантастика, триллер, драма, BDRip] [Альтернативная версия / Alternative Cut] Dub
Url: https://rutracker.org/forum/viewtopic.php?t=4261657
Link: https://rutracker.org/forum/dl.php?t=4261657
Size: 1.46 GB
Seed: 140140

ID: 2
Title: Я – легенда / I Am Legend (Френсис Лоуренс / Francis Lawrence) [2007, США, Фантастика, триллер, драма, BDRip] [Театральная версия / Theatrical Cut] Dub
Url: https://rutracker.org/forum/viewtopic.php?t=4749161
Link: https://rutracker.org/forum/dl.php?t=4749161
Size: 1.46 GB
Seed: 7878

ID: 3
Title: Я - легенда / I Am Legend (Френсис Лоуренс / Francis Lawrence) [2007, фантастика, триллер, драма, BDRip 720p] [Альтернативная версия / Alternative Cut]
Url: https://rutracker.org/forum/viewtopic.php?t=3375799
Link: https://rutracker.org/forum/dl.php?t=3375799
Size: 4.85 GB
Seed: 3737

Dowload ID: 1
Download --> /home/madest92/[rutracker.org].I am legend.torrent
```
