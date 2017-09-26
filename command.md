## md5のあってるかどうかチェック
```
diff (md5 ~/Downloads/xubuntu-16.04.3-desktop-i386.iso | cut -d" " -f 4 | psub) (echo "a3901d56a46d84bb660826a7add029ae" | psub)
```
