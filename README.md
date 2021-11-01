# [KDM Book](https://k-datamining.github.io/dm-book/intro.html)

[動画](https://www.youtube.com/channel/UCFy3VBvZBeE9bN0F2sxF8rg)で使用したコードを公開するための jupyter-book([link](https://k-datamining.github.io/dm-book/intro.html))

## build

```
nbqa black kdm-book
jupyter-book build kdm-book
ghp-import -n -p -f kdm-book/_build/html
```
