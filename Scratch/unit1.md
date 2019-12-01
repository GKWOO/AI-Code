# 第一课 Scratch 的基本应用
### 这堂课讲解Scratch的基本语句，通过这些语句实现一个简单的例子。<br>如下图，我们使这只可爱的猫会行走，碰到边缘后会往回走。然后当猫向左时会变颜色，反之不变色。

![Download](/Scratch/resource/program0.gif)

### 1. 界面左边是程序视图，中间是程序语句图形，右边是程序主题。选择事件把“当绿旗被点击”拉到右边程序主题，这是程序的开始。

![Download](/Scratch/resource/program1.gif)

<br><br>

### 2. 我们先让右边的猫动起来。选择运动，拖动“移动”图形与之前的开始拼接。如下图，点击后猫猫明显向右移动了。

![Download](/Scratch/resource/program2.gif)

<br><br>

### 3. 使用循环实现猫猫向前移动。点击控制，拖动“重复执行”并把“移动”放到循环体中，点击运行，猫猫向前移动，但移动距离并不远，因此我们修改循环次数使猫猫走得更远。

![Download](/Scratch/resource/program3.gif)

<br><br>

### 4. 猫猫终于能向前移动了，但碰到边缘就不动了，现在就让我们让它碰到边缘向回走。点击移动，拖动“碰到边缘就反弹”到循环后。

![Download](/Scratch/resource/program4.gif)

<br><br>

### 5. 如下图，即使把重复次数改为100后碰边后停顿一段时间后转向而不是来回走。

![Download](/Scratch/resource/program5.gif)

<br><br>

### 6. 不会来回走是因为碰到边缘反弹在循环体外面，因此会循环移动100次后才判断是否到边缘然后反弹。只需要把“碰到边缘”拖动到循环体中就能实现来回走了。

![Download](/Scratch/resource/program6.gif)

<br><br>

### 7. 虽然实现了来回走，但返回时是倒过来的。我们只需要在程序开始后把“旋转模式设置为左右”便能实现来回走而不倒立。

![Download](/Scratch/resource/program7.gif)

<br><br>

### 8. 如何能使猫猫移动时有走动的动作？点击外观把“下一个造型”拖动到循环体中便有了移动的动作了。

![Download](/Scratch/resource/program8.gif)

<br><br>

### 9. 通过方向判断来改变猫猫的颜色来学习判断语句。先选择运动然后勾选方向，在显示方向上显示了当猫猫向左时是-90，向右时是正90.因此选择控制把“如果否则”拖动到循环体中，选择“运算”然后把判断相等的图形拖到判断条件中，然后点击运动把“方向”拖动进判断中，判断方向是否等于90，如果是就改变颜色，反之把颜色设置为0

![Download](/Scratch/resource/program9.gif)

