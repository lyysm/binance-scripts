<!--
 * @Author: liuyin
 * @Date: 2022-08-17 23:26:27
 * @LastEditTime: 2022-08-17 23:29:01
 * @FilePath: /binance-scripts/README.md
 * @Description: binance 相关脚本
-->

### wodl

binance wodl 猜字游戏脚本

```
➜  wodl git:(master) ✗ python3 wodl.py -h
usage: wodl.py [-h] [-new NEW] [-l LENGTH] [-n NOLETTER] [-g GUESSED_LETTER] [-e ERROR_POS_LETTER]

binance 猜字游戏

optional arguments:
  -h, --help            show this help message and exit
  -new NEW, --new NEW   开始新游戏并指定单词长度
  -l LENGTH, --length LENGTH
                        设置单词长度
  -n NOLETTER, --noletter NOLETTER
                        添加不包含的字母
  -g GUESSED_LETTER, --guessed_letter GUESSED_LETTER
                        添加已猜中的字母
  -e ERROR_POS_LETTER, --error_pos_letter ERROR_POS_LETTER
                        添加已知存在但位置错误的字母
```
