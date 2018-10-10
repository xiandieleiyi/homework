# 制作 HTML5 游戏
## 一.安装Construct 2
Construct 2 is a powerful ground breaking HTML5 game creator designed specifically for 2D games. It allows anyone to build games — no coding required!
## 二.新建工程
打开Construct 2，可以看到一个类似Microsoft Office 2010的界面。点击左上角File（文件）按钮打开“文件”菜单，选择New（新建）建立工程。

![Alt text](https://www.scirra.com/images/articles/filenew.png)
## 三.设置背景
事先选好一张图片作为背景并保存在电脑中。在layout画布里双击，弹出插入对象对话框。在该对话框中双击Tiled Background对象。

![Alt text](https://www.scirra.com/images/articles/insertobject.png)
在布局的任何位置点击，我们在布局中间差不多位置点击，弹出Texture editor对话框，我们点击打开文件夹图标，把选好的背景载入。调整背景大小，使其充满整个布局。
## 四.添加对象
1. 添加一层
布局可以有多个层，可以用于对象进行分组。在一个游戏中，如果我们希望所有的东西都显示在平铺的背景上，这样我们就可以为我们的其他对象另做一层。
单击图层标签，单击绿色的‘Add’图标为我们的其他对象添加一个新的层。

![Alt text](https://www.scirra.com/images/articles/layerstab.png)
![Alt text](https://www.scirra.com/images/articles/layersbar.png)

2. 添加对象
对于这些对象，我们将使用sprit对象。它只显示一个纹理，你可以移动，旋转和调整大小。游戏通常是由精灵物体组成的。这个过程类似于插入平铺背景.
这些对象将被称为sprit,sprit2,sprit3,...。这不是很有用-事情会很快变得像这样混乱。重新命名对象，视情况而定。可以通过选择对象，然后更改名字，姓名属性栏中的属性：

![Alt text](https://www.scirra.com/images/articles/objectname.png)
## 五.添加行为
行为是构造2中预先打包的功能。例如，可以添加平台对象的行为，而实心行为在地板上，你可以立即跳来跳去，就像一个盘子。您可以在事件中做同样的事情，但它需要更长的时间，而且如果行为已经足够好的话，也没有意义！在属性栏中，注意行为类别。点击添加/编辑那里sprit的行为对话框将打开。

![Alt text](https://www.scirra.com/images/articles/openbehaviors.png)
单击“行为”对话框中的绿色“添加行为”图标。双击你所想要执行的行为加进去。

![Alt text](https://www.scirra.com/images/articles/add8dir.png)
## 六.添加事件
首先，单击活动单1选项卡的顶部切换到事件表编辑器。事件列表称为事件表，您可以有不同的事件表，为您的游戏的不同部分，或为组织。事件表也可以“包括”其他事件表，例如，允许您在多个级别上重用事件。

![Alt text](https://www.scirra.com/images/articles/eventsheettab.png)
事件包括条件，测试是否满足了某些标准，例如。“空格键坏了吗？”如果所有这些条件都满足了，事件行为才能进行。在操作运行后，任何子事件它们可以测试更多的条件，然后运行更多的操作，然后运行更多的子事件，等等。使用这个系统，我们可以为我们的游戏和应用程序构建复杂的功能。
1. 双击事件工作表中的空格。这将提示我们添加条件参加新的活动。

![Alt text](https://www.scirra.com/images/articles/newevent_2.png)
2. 不同的对象有不同的条件和操作，这取决于它们能做什么。还有系统对象，它表示构造2的内置功能。双击系统对象，如所示。然后，对话框将列出系统对象的所有条件：

![Alt text](https://www.scirra.com/images/articles/everytickcnd.png)
3. 单击添加动作链接到事件的右侧。(确保得到加法行动链接，不添加事件链接下面的链接，这将再次添加一个完全不同的事件。)
![Alt text](https://www.scirra.com/images/articles/addactiondlg.png)
与添加事件一样，我们有相同的对象列表可供选择，但这一次用于添加行动。尽量不要混淆添加条件和添加操作！
![Alt text](https://www.scirra.com/images/articles/playersetanglepos.png)
## 七.为游戏添加难度
至此，一个简单粗糙的游戏就完成了。在此基础上，我们可以通过再添加一些事件，或改变一些事件的条件或结果来增加游戏的难度和趣味性。例如：提高怪物的智慧；定时产出新的怪物；增加计分规则并显示分数......
## 八.我的成品展示
