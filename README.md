# mame-categories
script to generate additional MAME Categories using libxml2 xpath 1.0 support

tool comes out of [this reddit post](https://www.reddit.com/r/MAME/comments/yqci1l/filter_only_perfectly_working_games_from_the/ivnzozd/?context=3)

## Usage
```
./generate filters/status-good
```

## MAME default UI usage
1. Copy the created ini file to your mame installation directory under `folders`
1. Load MAME, double click Categories
1. Cycle through to the ini of your choice
1. List will be filtered

## Create your own filter
See the example filters in the `filters` folder of this tool and consult the [xpath spec](https://www.w3.org/TR/1999/REC-xpath-19991116/)
