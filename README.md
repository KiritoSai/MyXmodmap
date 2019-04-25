# MyXmodmap
Ubuntu中通过xmodmap 将super和alt键替换位置
```
xmodmap ~/.Xmodmap
```
将操作写入bashrc中
```
#执行按键的重新映射
if [ -f ~/.Xmodmap ]; then xmodmap ~/.Xmodmap; fi
```

