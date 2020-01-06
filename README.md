# 毕业纪念app


Title|Content
-----|:------
发布日期|2019-12-10
名称|毕业纪念app
文档状态|进行中
文件主人|	谢颖
领头的设计师|	谢颖
领头的开发者|	谢颖
领头的测试者|	谢颖

### 价值主张练习
**一句话版本**
一个张照片或一条语音，让你找到指定同学信息与回忆。

**一分钟版本**
本产品以学校毕业的学生为目标用户，目的是为了让毕业的学生有一个线上的校园回忆存放地方，并能在你想他的任何时刻迅速找回你同学的相关信息。在经过市场调查后我们发现，现今市场上大多数毕业纪念册app大多只有单一的照片储存、视频记录功能，比较有特点的最近比较火的照片合成功能。但在人脸识别和语音识别方面毕业纪念册app大多都没有涉及。所以本产品的亮点与价值就在于我们的人脸识别以及语音识别功能：第一个主要功能是人脸识别功能，通过运用人脸识别api，找到相册中同学的照片进行人脸识别，即可返回相关个人信息，再也不用怕多年之后找不回当年的他，并且可以自动将照片分类。第二个次要功能是语音识别功能，通过运用语音识别api，说出同学的名字，即可找到相关同学的联系方式和照片。第三个是，语音合成功能，通过识别app留言板上的语音进行文字转化，更清晰的看到当时的留言记录。
### 产品介绍
“毕业纪念app”是一款提供给已毕业的学生找回当年同学的联系方式，和回忆浏览当时学生时代的照片、音视频等。
### 背景
学生时代是每个人心中不可磨灭最美好的记忆，但随着时间的推移想要再次翻看浏览以前的回忆就变得非常难。照片和其他回忆内容的保存也十分麻烦，以及同学的联系方式可能也会改变，此时非常需要一款可以保存记录这些记忆，并且提供更新个人信息联系方式的平台，让其他同学能方便联系到ta。且该app通过用户上传的照片进行人脸识别，可将相册进行分类，用户可以找到专属自己相册的回忆，同时也能共享相册，找回集体记忆。

### 产品目标
- 找回同学联系方式：运用人脸识别api找到对应同学的联系资料
- 输入语音找到对应想找信息，并跳转到相应页面（语音说出“张三”,即可跳转到有关张三的信息页面和有关照片）：运用语音识别api
- 将语音留言板转化为文字留言：运用语音合成api

### PRD 价值主张设计
#### PRD1.加值宣言
本产品旨在通过运用百度AI中的部分功能（人脸识别、语音识别、语音合成）帮助毕业后的同学轻易找回当年好友的联系方式，回忆自己的学校生活。
- 人脸识别API对本产品价值部分在于：不需要翻毕业大合照中的人脸去寻找他的相关信息，只需要上传一张他的照片，即可以显示他的相关信息及联系方式。
- 语音识别API对本产品价值部分在于：不需要手动查找有关自己或他人的信息，只需要语音输入相关名字，即可查询到此人的联系方式和有关照片。
- 语音合成API对本产品价值部分在于：不需要一条一条语音听，通过一键转化，就能将语音信息转化为文字信息。

#### PRD2.核心价值
- 人脸识别API：最小可用产品为识别出图中人脸，显示此人的相关信息和相片分类。
- 语音识别API：最小可用产品为识别语音搜寻，显示相关的信息和照片。
- 语音合成API：最小可用产品为将语音留言信息转化为文字信息。

#### PRD3.核心价值与用户痛点 
- 纸质版纪念册容易不见、易受环境毁坏
- 只想浏览有关自己或他人在内的照片，照片太多太杂没办法分类
- 想找回同学的联系方式但别人已更换了联系方式

#### PRD4.人工智能概率性与用户痛点
人工智能概率性|用户痛点
-------------|:------
语音识别出现相同名字的人|相同名字的人信息错乱
人脸识别api|想快速得到照片中同学信息或记不清照片中同学名字


#### 需求列表及人工智能API加值
需求列表|人工智能api加值|重要程度
-------|:-------------：|:--------
想快速得到照片中同学信息或记不清照片中同学名字|人脸识别api|非常重要
照片太杂太乱，想要将相片可以按照人来分类|人脸识别api|重要
想要找到相关同学张三的信息，不知从何找起|语音识别api|重要
语言留言的信息太多，听不完|语音合成api|重要
