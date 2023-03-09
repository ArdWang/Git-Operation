# Git-Operation
This is git Operation

##### 查看代码之前代码功能
1. cd到指定的文件夹，进行 

```

xxxMac:xxxx_kotlin rnd$ git branch -a
* 930
  accutherm-2023-2-7
  androidx-version-1.0.1
  lhbeacon-v1.0.1
  master
  remotes/origin/930
  remotes/origin/HEAD -> origin/master
  remotes/origin/accutherm-2023-2-7
  remotes/origin/androidx-version-1.0.1
  remotes/origin/lhbeacon-v1.0.1
  remotes/origin/master
  


  
```

进行回退的操作此时代码已经回退了

```
xxxxiMac:xxx_kotlin rnd$ git reset --hard d609e3d
HEAD is now at d609e3d update rnd 2022/10/18
ThermodeiMac:RilBeacon_kotlin rnd$ 
```

然后再进行恢复到最新的就可以 记住 commitid github会有显示

```
xxxiMac:xxxx_kotlin rnd$ git reset --hard f81ed6a
HEAD is now at f81ed6a update rnd 2023/2/7

```

git push --force origin HEAD


