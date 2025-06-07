graph TB
    UI[用户界面层(UI)<br>控制按钮、图形展示]
    Controller[控制逻辑模块(Controller)]
    Model[物体模型<br>（子弹/球）]
    Event[事件驱动<br>（时钟/鼠标）]
    Physics[物理计算模块(Physics)<br>位移/速度/碰撞检测]

    UI --> Controller
    Controller --> Model
    Controller --> Event
    Model --> Physics
    Event --> Physics
