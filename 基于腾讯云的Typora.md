## 术前准备

+ 安装好 *Typora* ： [提取码：h9bb](https://pan.xunlei.com/s/VNB_VLRHiLk6wUoyXr4mCWM6A1)    *PicGo*  ：[提取码：k77e](https://pan.xunlei.com/s/VNB_WALBOdxS0Hkp49VZlZT_A1)

+ 环境配置 *nodejs*：https://nodejs.org/en/

+ *Gitee* 账户：https://gitee.com/

## 开搞

### 01.配置完*nodejs*

```node --version
C:\>node --version
v16.17.0
C:\>npm --verison
8.15.0
```

### 02.配置腾讯云对象储存

**创建储存桶**

+ 点击 `储存桶列表`-> `创建储存桶` -> *进行以下配置*

![image-20220910162226526](https://dreamin-1312842512.cos.ap-guangzhou.myqcloud.com/image-20220910162226526.png)

+  访问权限选择**公有读私有写**，否则图片无法读取，其他的根据自己往下填写就可以。 地域建议离你所在的位置越近越好。

### 03.获取密钥

+  腾讯云头像–>[访问管理](https://cloud.tencent.com/product/cam?from=10680)–> API密钥管理，创建密钥，就会生成 **APPID、SecretId和SecretKey**

![image-20220910162556056](https://dreamin-1312842512.cos.ap-guangzhou.myqcloud.com/image-20220910162556056.png)

### 04.*PicGo*配置

+ 点击`图床设置`-> `腾讯云COS`-> 填写好刚刚的密钥和存储桶的名称，记得**设置COS版本为V5**



![image-20220910162842723](https://dreamin-1312842512.cos.ap-guangzhou.myqcloud.com/image-20220910162842723.png)

+ 自定义域名和存储路径未进行CDN加速可默认为空

**上传测试**

![image-20220910163005832](https://dreamin-1312842512.cos.ap-guangzhou.myqcloud.com/image-20220910163005832.png)

**查看文件是否有保存**

![image-20220910163038658](https://dreamin-1312842512.cos.ap-guangzhou.myqcloud.com/image-20220910163038658.png)

### 05.Typora配置

+ 点击 `文件`->  `偏好设置` -> `图像`

![image-20220910163202939](https://dreamin-1312842512.cos.ap-guangzhou.myqcloud.com/image-20220910163202939.png)

+ 如上图配置即可使用

## 参考

+ https://blog.csdn.net/haojie_duan/article/details/120400386

+ https://cloud.tencent.com/developer/article/1834573
