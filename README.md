# Free-storage---Mac
Record commands for fast free up Mac space

## 进入Terminal
### 点击spotlight search
![image](https://github.com/harryhaoranhub/Free-storage---Mac/assets/94785163/7818242b-385c-4d2d-a85a-e4b28c4337b8)

### 输入Terminal （中文版输入：终端）
<img width="1512" alt="image" src="https://github.com/harryhaoranhub/Free-storage---Mac/assets/94785163/3afe76ac-1628-495a-b0db-382d0902dd47">


### 在这个页面里输入指令

<img width="570" alt="image" src="https://github.com/harryhaoranhub/Free-storage---Mac/assets/94785163/9688965f-9918-441b-8a3a-384b929843a6">

## 指令
将下列指令复制粘贴到terminal终端中，按回车即可
删除之后电脑还会慢慢生成这些文件，所以空间不够了就删一下
### 1. 删除系统日志（如果空间不是特别紧张，直接跳到4）
点代码块后面那个小窗可以直接复制
```
sudo rm -rf /private/var/log/*
```
<img width="570" alt="image" src="https://github.com/harryhaoranhub/Free-storage---Mac/assets/94785163/61502feb-2c4e-46f0-898e-cf3915ddbf49">

### 2. 删除临时文件（如果空间不是特别紧张，直接跳到4）
```
sudo rm -rf /private/var/tmp/
```

### 3. 删除快速查看缓存（如果空间不是特别紧张，直接跳到4）
```
sudo rm -rf /private/var/folders/
```

### 4. 清除系统缓存（这个删很大，可以常用）
```
sudo rm -rf ~/Library/Caches/*
```
<img width="570" alt="image" src="https://github.com/harryhaoranhub/Free-storage---Mac/assets/94785163/796affcc-d8fb-44c8-90ea-b5224d3a7dca">

### 注意
如果输入指令后电脑遇到图标不显示等问题，重启电脑

## 微信数据
微信数据量很大，可以经常删删不必要的

### 点开聊天框，找到图片或文件，右键点击图片，进入show in folder
<img width="660" alt="image" src="https://github.com/harryhaoranhub/Free-storage---Mac/assets/94785163/ea57b196-282d-4ac8-9a5b-2bffea16ad4f">

### 文件夹中会显示和对方所有的图片，可以选不必要的移到bin
<img width="920" alt="image" src="https://github.com/harryhaoranhub/Free-storage---Mac/assets/94785163/866ff073-7844-4a9c-89fe-66b21a415e4e">

右键选中图片move to bin
<img width="759" alt="image" src="https://github.com/harryhaoranhub/Free-storage---Mac/assets/94785163/82264869-8b0b-42dd-bf0f-e9016ff9f1ad">

### 别忘了 empty bin
<img width="920" alt="image" src="https://github.com/harryhaoranhub/Free-storage---Mac/assets/94785163/10bb67f3-a244-4c1c-a542-cd898800d7a5">

### 另有直接清空微信占用内存的方法，但要确定微信电脑端没有任何重要文件或已经将文件备份







