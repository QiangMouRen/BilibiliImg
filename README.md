## 批量下载bilibili高清壁纸

### 说明

批量下载bilibili高清壁纸 (h.bilibili.com)

环境：**php>7.0*

### 使用

命令行下执行以下命令 

```shell
git clone https://github.com/QiangMouRen/foreach_download_bilibili_image.git
# 如果为安装git 请执行 yum install git -y
cd foreach_download_bilibili_image
php get.php
```

等待执行完毕

图片保存目录默认为 ./images 

自定义保存目录 可以在命令行下执行

```shell
php get.php path='自定义目录/'
```


下载完毕的本地图片路径都存放在 ./data.json 文件里面


用下载来的图片做所谓的随机图片接口，也就是访问一次显示不同图片的接口


打开 index.php 文件修改 $url 变量为自己的域名 以/结尾

将图片和index.php上传服务器 

访问 域名/index.php 看看？

### bug

如果有人如何问题，可以提交issue
