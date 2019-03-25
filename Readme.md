

---

Modified from https://github.com/quanweiGithub/Ubuntu-China-Source

现在换源之后将不自动进行系统更新

---

（my repo）
命令行安装
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/seognil-forker/Ubuntu-China-Source/self/ChangeSource.sh)"
```

---

支持自动配置的命令行安装

修改后续参数 `${ver} ${src}`，比如：
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/seognil-forker/Ubuntu-China-Source/self/ChangeSource.sh) 18 ali"
```

可选参数列表为：
```
ubuntu 版本：
  14: 14.04
  16: 16.04
  18: 18.04
可选的源：
  ali 阿里
  thu 清华
  163 网易
```
