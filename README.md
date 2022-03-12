# PicBed
个人图床，没啥隐私。。。
# 新建一个github仓库
![](https://cdn.jsdelivr.net/gh/aProfessor23/PicBed@main/img/202203122108527.png)
# 生成一个Token
![](https://cdn.jsdelivr.net/gh/aProfessor23/PicBed@main/img/202203122110499.png)
![](https://cdn.jsdelivr.net/gh/aProfessor23/PicBed@main/img/202203122112561.png)
![](https://cdn.jsdelivr.net/gh/aProfessor23/PicBed@main/img/202203122116356.png)
![](https://cdn.jsdelivr.net/gh/aProfessor23/PicBed@main/img/202203122119353.png)
# 配置 PicGo 并使用 jsdelivr 作为 CDN 加速
```
设定仓库名：按照用户名/图床仓库名 的格式填写
设定分支名：main
设定 Token：粘贴之前生成的Token
指定存储路径：填写想要储存的路径，如 img/，这样就会在仓库下创建一个名为img的文件夹，图片将会储存在此文件夹中
设定自定义域名：它的的作用是，在图片上传后，PicGo 会按照自定义域名+上传的图片名的方式生成访问链接，放到粘贴板上，因为我们要使用 jsDelivr 加速访问，所以可以设置为https://cdn.jsdelivr.net/gh/用户名/图床仓库名@分支 #默认是main
```
![](https://cdn.jsdelivr.net/gh/aProfessor23/PicBed@main/img/202203122127330.png)
# 完事！！！
