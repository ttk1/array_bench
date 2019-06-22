# ArrayBench
配列操作のベンチマークをとる

## 計測方法
bashのtimeコマンドを使う

```bash
TIMEFORMAT='%R'
measured=$((time $target ;) 2>&1)
```

```bash
# example
$ target='sleep 5'
$ TIMEFORMAT='%R'
$ echo $((time $target ;) 2>&1)
5.028
```

## ベンチマーク内容

## 言語別
### bash

### python

### java