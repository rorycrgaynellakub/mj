# Midjourney以图生图详细教程（6个案例解析）

学习如何使用Midjourney实现以图生图的过程，通过上传图片结合关键词生成新图。本教程提供了具体步骤和六个案例，助你快速掌握这项技术。

## 基础介绍

本篇文章将介绍如何利用Midjourney完成图生图的方式，简而言之，就是以我们上传的图片为基础，再结合一些关键词，如风格、结构、颜色重新生成图片。本次会以一些案例为中心手把手的教学，争取让大家一学就会！

## 准备工作

1. 科学上网，能登录Midjourney。
2. 准备清晰的图片（最好清晰显示五官）。

## 垫图步骤

### 获取图片链接

#### 方法1：
1. 点击输入框左侧的加号图标，然后点击上传文件。
2. 选择你想要垫的图片，点击打开。
3. 图片出现在框内时，点击回车发送。
4. 右键图片，选择复制链接。

#### 方法2：
1. 复制你想要垫的图片，点击输入框，按Ctrl+V粘贴图片。
2. 点击回车发送，右键图片，复制图片链接。

### 使用图片链接

1. 在/imagine命令的prompt框中输入图片链接。可以用一张或多张图片作为基础，注意图片链接之间要打一个空格。
2. 输入描述词，记得要在图片链接后打一个空格再输入描述词。
3. 输入参数（可选），如图片尺寸等，输入完参数后点击回车键发送。

例如：`--iw 0.5~2` 参数决定上传图片的参考程度。

## 案例展示

### 案例1：

以女生图片垫图，用niji5模型生成新的图片。
- 原图：
![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/18cd27ce-f0fb-46f5-a011-84e38381a3f6)

- prompt: `https://s.mj.run/h84Xh2GHYdM a beautiful girl --q 2 --niji 5 --s 750`
- 生成图片：
![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/a016c31b-3a45-4605-9aed-c69ee4ad29f8)


### 案例2：

用一张女生图片和一张风景图片垫图生成新图。
- 原图：
![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/8da91b50-ce5d-40f5-b177-5e5ac14bb2da)

![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/35213dee-52d4-48a7-a2f6-f756a34565c1)

- prompt: `https://s.mj.run/h84Xh2GHYdM https://s.mj.run/p6lXZHN6fK4 --q 2 --niji 5 --s 750`
- 生成图片：
![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/11e9a00c-fdd6-400b-97a8-3362a28fba9d)


### 案例3：

用小狗和草原风景图垫图生成新图。
- 原图：
![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/22ecb909-064d-45be-a237-84c3693e67f0)

![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/7b70f770-8f92-4cde-a3ac-d3ab2cffdfa1)

- prompt: `https://s.mj.run/CJqurC2M9QE https://s.mj.run/aE31qvuVg6c A lovely dog is on the grassland --iw 2 --q 2 --v 5`
- 生成图片：
![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/ef167386-52bc-4c07-84b6-dc87fca3543d)


### 案例4：

用现代女生和二次元女生图片生成新图。
- 原图：
![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/5c16ced9-462f-49eb-b000-22445a0b29ee)

![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/0c8327f0-5f4c-4ba7-98ce-e888120b804d)

- prompt: `https://s.mj.run/bEutS3bmP90 https://s.mj.run/9Ymxz9V4HD0 --q 2 --v 5 --s 750`
- 生成图片：
![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/1bad4d56-fcd7-4314-a66d-88a6284e0f95)


### 案例5：

用小狗图片垫图生成新图片。
- 原图：
![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/b851e184-f9c8-496c-9177-92c14411cbda)

- prompt: `https://s.mj.run/CJqurC2M9QE a cute dog, 3D --q 2 --niji 4`
- 生成图片：
![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/16cc78ac-64bb-4f09-8c16-dc3f81b90fc5)


### 案例6：

利用垫图生成产品图。
- 原图：
![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/85ad9b8e-71b8-4926-b7e5-c70ee8dd3269)


![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/aa6a3d36-99d9-4b05-8650-c478fd638999)


- prompt: `https://s.mj.run/SqYLfJb58mg https://s.mj.run/5DRdhz0sioI New Canon 200D2, SLR camera, white, detailed detail, one leaf, misty blue background, super detailed --iw 2 --seed 4145808824 --q 2 --v 5`
- 生成图片：
![image](https://github.com/rorycrgaynellakub/mj/assets/169983353/41da59ac-d58c-40a3-b1c0-b7599f9453a1)


推荐一个虚拟信用卡开卡平台，包含香港、美国万事达VISA等多种卡头，0月费使用门槛极低，微信支付宝均可开通使用。支持开通各类海外平台：ChatGPT、Netflix、OnlyFans、Ebay、Shopify、Github、TikTok、Paypal 等各类订阅海淘平台。[点击查看详情](https://gpt.fomepay.com/#/pages/login/index?d=Q3DD80)

