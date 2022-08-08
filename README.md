# Ruizhe Zhao Portfolio
Projects

# [Project 1: Meltybrain格斗机器人](https://github.com/laozhao43/Meltybrain_Bot_CNMB) 
* 设计并建造 1.36kg 级别格斗机器人，移动方式为旋转平移
* 用 Arduino 编程，读取传感器和接收机信号。算法会根据传感器数据计算出当前转速和当前朝向并控
制机器人在旋转的同时移动。通过蓝牙模块发送实时数据给电脑
* 用 Python 处理回传数据，进行线性回归，并得出一组常数来校准加速计
* 用 SOLIDWORKS 建模，并进行结构设计，受力分析和拓扑优化。机器人在满油门下可以储存 130J
的旋转动能，武器尖端线速度可以达到 100km/h
* Seattle Bot Battles 比赛战绩：3 赢 2 输

![](/images/positions_by_state.png)


# [Project 2: ](https://github.com/PlayingNumbers/ball_image_classifier) 
For this example project I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sports from a certain country. They could take a picture of a ball and an app could serve them some information about the history and rules of the game. This is the underlying model for building something with those capabilities. 

I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results. 

![](/images/matrix_results.png)
