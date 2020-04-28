# 自动驾驶技术

<p align="left" ><img height="200" src="/imgs/selfdriving.png"/></p>

<table>
<tr><th colspan="4">自动驾驶技术</th></tr>
<tr><th width="250">1.环境感知</th><th width="250">2.定位与地图构建</th><th width="250">3.路径规划</th><th width="250">4.运动控制</th></tr>
<tr>
<td><ol>
    <li><details>
    <summary><a href="#cv">计算机视觉</a></summary><p><ol>
    <li>相机标定</li>
    <li>梯度和颜色空间</li>
    <li>深度学习和计算机视觉</li>
    <li>支持向量机</li>
    <li>决策树</li>
    <li>目标检测</li>
    <li><i>车道寻找项目</i></li>
    <li><i>车辆检测和追踪项目</i></li></ol></p>
    </details></li>
    <li><details>
    <summary><a href="#dl">深度学习</a></summary><p><ol>
    <li>神经网络基础</li>
    <li>线性回归</li>
    <li>线性分类</li>
    <li>深度神经网络</li>
    <li>卷积神经网络</li>
    <li>TensorFlow</li>
    <li>LeNet</li>
    <li>Keras</li>
    </ol></p>
    </details></li>
    <li><details> 
    <summary>传感融合</summary><p><ol>
    <li>卡尔曼滤波</li>
    <li>扩展卡尔曼滤波</li>
    <li>无迹卡尔曼滤波</li></ol></p>
    </details></li>
    </ol>
    </td>    
<td><ol>
    <li><details>
    <summary><a href="#loc">定位</a></summary><p><ol>
    <li>马尔可夫定位</li>
    <li>粒子滤波</li></ol></p>
    </details></li>
    <li><details>
    <summary>SLAM</summary><p><ol>
    <li>EKF-SLAM</li>
    <li>Fast-SLAM</li></ol></p>
    </details></li>
    <li><details> 
    <summary>高精地图</summary><p><ol>
    <li></li>
    <li></li></ol></p>
    </details></li>
    </ol>
    </td>
<td><ol><li>路径查找</li><li>预测</li><li>行为规划</li><li>轨迹生成</li></ol></td>
<td><ol><li>运动模型</li><li>PID控制</li><li>MPC</li></ol></td>

</tr>
<tr><th width="250">5.软件系统</th><th width="250">6.硬件系统</th><th width="250">7.系统安全</th><th width="250">8.仿真模拟</th></tr>
<tr>
<td><ol><li>ROS</li><li>RTOS</li><li>Apollo</li><li>Autoware</li></ol></td>
<td><ol><li>激光雷达</li><li>毫米波雷达</li><li>GPS</li><li>IMU</li><li>摄像头</li></ol></td>
<td><ol><li>功能安全</li><li>技术安全概念</li><li>危险分析和风险评估</li><li>软件和硬件安全</li></ol></td>
<td><ol><li>CARLA Simulator</li></ol><img height="50"/></td>
</tr>

</tr>
<tr><th width="250">9.基础知识</th><th width="250">10.相关工具</th><th width="500" colspan="2">11.相关论文书籍</th></tr>
<tr>
<td><u>数学:</u><ol><li>微积分</li><li>概率论与统计学</li><li>线性代数</li></ol>
    <u>编程语言:</u><ol><li>C/C++</li><li>python</li></ol></td>
    <td><ol><li>Docker</li></ol></td>
    <td colspan="2"></td>

</tr>

</table>

----------



## 定位与地图构建
1. 定位<a id="loc"></a>
   1. 马尔可夫定位
   2. 粒子滤波
2. SLAM
   1. EKF-SLAM
   2. Fast-SLAM
3. 高精地图

-----------

**目录**
1. [【环境感知】](#perception)
   1. [计算机视觉](#cv)
   2. [深度学习](#deepl)
   3. [传感融合](#fusion)
2. [【定位与地图构建】](#lm)
   1. [定位](#localization)
   2. [SLAM](#slam)
   3. [高精地图](#hdmap)
3. [【路径规划】](#pathplan)
   1. [路径查找](#)
   2. [预测](#)
   3. [行为规划](#)
   4. [轨迹生成](#)
4. [【运动控制】](#motioncontrol)
   1. [运动模型](#model)
   2. [PID控制](#pid)
   3. [MPC](#mpc)
5. [【软件系统】](#software)
   1. [ROS](#ros)
   2. [RTOS](#rtos)
   3. [Autoware](#)
   4. [Apollo](#apollo)
6. [【硬件系统】](#hardware)
   1. [激光雷达](#)
   2. [毫米波雷达](#)
   3. [IMU](#)
   4. [GPS](#)
   5. [摄像头](#)
7. [【系统安全】](#safety)
   1. [功能安全](#)
   2. [技术安全概念](#)
   3. [危险分析和风险评估](#)
   4. [软件和硬件安全](#)
8. [【模拟仿真】](#simulator)
   1. [CARLA Simulator](#carla)
9. [【基础知识】](#basics)
   1. [数学](#math)
      1. 微积分
      2. 概率论与统计学
      3. 线性代数
   2. [编程语言](#prolan)
      1. C++
      2. python
10. [【相关论文】](#paper)
     
    

---------------------



