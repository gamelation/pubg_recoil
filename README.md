# pubg_recoil
绝地求生压枪脚本

2018-02-23:<br>
辣鸡blue asshole,把把神仙打架，弃了弃了<br>

2018-01-19: <br>
脚本用了几个月了,没有被封,虽然kda大约从1升到2了,但菜还是菜,反应、水平压枪方面是靠脚本解决不了的.<br>
几个建议:<br>
  1. 尽量使用m4,scar,ump9,配件尽量齐,有m4的屁股就用m4,没配件的m4比ak还难用.<br>
  2. 用三角握把.<br>
  3. 不要使用ak,水平太难压了.<br>

init: 
  1. 本脚本的作用是在用户按下鼠标的时候自动压枪
  2. 参数及计算方法参考的是github上那个罗技鼠标宏
  3. 鼠标下移是调用DD XOFT虚拟鼠标,驱动级,但不排除被封的可能
  4. 有3种枪械模式:akm, m4a1, scar,按v切换
  5. 有2种准镜模式,基本(红点、全息)和4倍,按n切换
  6. 开始和暂停按p
  7. 有人反映win7下有bug,我不准备管了,估计以后也不会更新了
  8. 怎么运行?可以打成fatjar,把两个dll放到jar的同层,**用管理员权限**打开cmd,java -jar xxx.jar
  9. dd74000x64.64.dll是dd虚拟鼠标的,jacob-1.18-x64.dll是语音的
  10. 默认准镜的灵敏度都是50,也可以修改代码中的参数
![demo](ab.gif)
