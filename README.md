# ADTemplate
iOS project template without storyboard

将所有文件夹复制到~/Library/Developer/Xcode/Templates/Project Templates文件夹中，重启XCode

.xcconfig文件配置方法（很奇怪的是我在Debug、Release的基础上新加了AdHoc真机调试配置，在第一次打开时PROJECT的Build Settings中是显示了，但是在Info里没有显示，第二次打开后才显示了出来，应该是XCode的一个Bug）

1、进入项目PROJECT设置

![](https://github.com/jiabin87428/ReadMeImage/blob/master/ECB38217-3A77-4E04-ADC0-A1C5EB05C784.png?raw=true)


2、选择并编辑各个配置对应的文件

注意，ConfigBase.xcconfig是通用配置，我在里面设置了App版本号，如果有其他通用配置要设置可以在这里设置，然后各个子配置文件中设置了App显示的名称（用来确认环境是否正确，最好每个配置设置特定的名称），还有一个BaseServiceURL，对应测试环境和正式环境，可以根据各自的项目设计来定义

![](https://github.com/jiabin87428/ReadMeImage/blob/master/FE612022-F386-481D-9B77-ACFB40B48F92.png?raw=true)

![](https://github.com/jiabin87428/ReadMeImage/blob/master/702D8944-DF32-4F75-8706-B4E63B83329B.png?raw=true)

![](https://github.com/jiabin87428/ReadMeImage/blob/master/5E35639E-2BBC-4C15-8E81-39A2854DD304.png?raw=true)