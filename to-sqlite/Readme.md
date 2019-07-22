# Terrain to SQLite
Convert a directory of terrain tiles to a sqlite database.

### How to use

```
python terrainsql.py -h
```

return:

```
usage: terrainsql.py [-h] [-d TILE_DIRECTORY] [-o OUTFILENAME]

optional arguments:
  -h, --help            show this help message and exit
  -d TILE_DIRECTORY, --tile_directory TILE_DIRECTORY
                        Specify the directory of terrain files.
  -o OUTFILENAME, --outfilename OUTFILENAME
                        Specify name and location of sqlite database.
```

usage example:

```
python terrainsql.py -d terrain -o test.db
```


