# PetFeeder
A product for feeding pets, dog, cat or other pets.[Function + PetMonitor]

This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.For more information, please check Tuya Developer Website.

## 一、方案标题
  自动宠物喂食器-PetFeeder
## 二、方案应用场景
### 背景：
    家里有一只7年猫龄的主子,已经伺候了整整七年!到了7年之痒之际!作为一名还算资深的铲屎官,有些时候总有一些不得已的时候! 
    譬如:
    过年过节总有不得不回老家,或者出门的时候,这时候主子吃喝拉撒怎么办? 
    公司临时决定让你出差半个月,家里的主子没人照顾怎么办? 
    疫情之下,万一中个招,被圈禁起来,主子又是孤身一猫怎么办? 
    托朋友搭人情,还要时时挂念着.真是挠心挠肺啊!!!!!! 
    时下年轻的朋友们,年老的长辈们,还有小朋友们很多都选择小动物来表达情感的寄托,也就衍生了对小猫,小狗,小兔子等等宠物的市场的拉动. 
    而对于传统意义上喂养对普通朝九晚六,特别是一线城市动不动就996的或者天天加班的打工人们,有点不切实际! 
    所以智能喂养,自动喂养器械应运而生. 
### 地点：
宠物家庭,宠物医院,宠物寄养屋
### 功能：
通过产品实现智能化投喂食物给宠物: 
#### 一期计划
1. 可以通过智能设备,手机,平板等,通过app进行手动投喂食物.
2. 通过APP实现分时段投食,设定投食间隔时间,定时定量进行投喂食物.
3. 亦可通过自带的语音识别模块,实现语音控制进行投喂食物.
4. 针对食盒内食量进行监控,缺食进行报警.
5. 远端语音对话,实现远程语音与宠物沟通. 
#### 二期计划
6. 扩展功能,后续扩展摄像头模组,集成云台,实现监控宠物行为.
### 方案：  
  初步方案,选定涂鸦三明治开发套件作为主控板不增加额外主控,后期根据实际需求以及必要性,酌情考虑是否增加功能更强大的主控来制作.
  本身三明治开发套件是基于语音以及wifi入网的套件,需要优先了解套件外围资源使用情况,看是否有多余IO,来实现称重,红外,以及后续摄像头模组的扩展.  
## 三、开发计划
1. 3月15前准备物料.  
  $ 涂鸦三明治开发套件  
  $ 5VDC减速电机  
  $ 厚纸箱手工磨具设计  
  $ 食盒称重计量  
2. 3月15-4月15日嵌入式固件开发、云端API对接开发.  
  $ 涂鸦协议  
  $ 涂鸦APP  
  $ 涂鸦MCU SDK  
3. 4月25日前整体调试.  
  $ 联调固件机械部分  
  $ 联调APP与云端部分  
  $ 联调APP到喂食器通路  
  $ 语音指令识别调试  
  $ 装备磨具完成整个产品.  
4. 4月30前完成.  
  $ 整备产品压力测试7天.  


参考同类产品模型:
https://youtu.be/riDFYJS5jQ4

<iframe width="1260" height="709" src="https://www.youtube.com/embed/riDFYJS5jQ4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
