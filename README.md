## 项目命令

### `npm install`
安装依赖

### `npm start`
运行App


## React-Practice题目描述

### 练习内容
- React基本概念，包括：state、props、组件的生命周期等
- React路由，包括：如何定义路由、如何页面跳转等
- 基本的JSX标签及写法
- Less的使用
- ES6语法

### 需求
- 对在线计算器页面进行组件划分，标记出组件的层次，并写出各个组件的名字
- 列出完成在线计算器的Tasking
- 在现有代码库的基础上，参照Mock-up完成：
    - 步骤1：Home页面及跳转
        - 点击在线计算器跳转到在线计算器页面
        - 点击在线倒计时器跳转到在线倒计时器页面
    - 步骤2：在线计算器页面
        - 0-9、加(+)、减(-)、乘(*)、等于(=)的按钮，输入和结果显示框
        - 基本的加、减、乘的操作
        - 点击0-9和运算符号时，在显示框显示数字和运算符号（只考虑两个数字运算的情况），点击等号输出结果
        - 数据输入：数字 符号 数字 =，显示结果。其他情况，清空输入
        - 实现一个清零键(Clear)，不管之前按下任何键后，按下清零键，清空输入
        - 底部有链接返回Home页面，返回Home页面后，再进入计算器，起始输出为空
    - 步骤3：在线倒计时器
        - 输入框：用于输入倒计时的秒数
        - 倒计时框：用于显示剩余时间，每间隔1秒数字减一，初始显示"Start"，倒计时结束显示"End"
        - 开始按钮：点击后根据输入的秒数开始倒计时，开始计时后，按钮不能再被点击。当开始计时时，只能等待结束，或者返回主页
        - 底部有链接返回Home页面，返回Home页面后，再进入倒计时器，需要重新输入并开始
        ```
