# NodeJS/javascript的计算平台
  Superlogic是一个基于NodeJS/javascript的计算平台。
  在这个平台上，用户可以快捷地开发出各种物联网，工业控制，数据采集的应用系统而设计者只需要会使用javascript 程序设计语言和HTML5.  
      这个项目的另一个重要的内容就是开发一种基于数据流/图形设计方式的编程工具，设计者可以像设计硬件原理图那样将预先设计的元件拖放到原理图上，并且连线。
开发环境就可以自动生成可以在NodeJS上运行的javascript程序。
它们有4部分组成：
 *  Linux/NodeJS的主处理器模块
 * 一系列Superlogic I/O模块
 * 一个高速总线
 * 一个基于图形/数据流开发环境
 
#  目的
  过去的十多年来，我们的团队一直开发各种嵌入式系统，非常的辛苦，一个小的应用系统也需要搭试电路，PCB设计，Keil 开发程序，jtag下载，一大堆工作。
修改应用程序往往也是非常麻烦的一件事。培养软硬件兼修的嵌入式工程师也需要很长的时间。教会了又很难留得住。
伴随着不断的吐槽，我们也一直寻找一种高效率的嵌入式系统开发技术，并且降低嵌入式系统开发的学习难度。以便更多的普通工程师也能开发嵌入式系统 。  
  NodeJS 进入了我们的视线范围，NodeJS的单线程，异步，基于事件的模式和嵌入式程序的架构非常相近。
最终，我们选择了NodeJS作为饼干控制的语言平台。
我们一开始的想法非常简单，开发一个类似ardunio这样的小电脑，模块化设计，javascript 编程。我们称它们为饼干(Biscuit)。为什么取这个名称呢，除了希望取一个耳熟能详的名称让人容易记得我们，还有一个原因是我们的系统将使用javascript 作为程序设计语言，java是印度尼西亚的爪哇岛的一种咖啡。而我们想喝咖啡必须来点饼干才是完美的下午茶。
没有几天，饼干系统的原型机就出来了。最早只是使用UART异步串口作为饼干之间的通信链路。在windows上的nodeJS作为主模块。开发了一个DMX512 的灯光控制器。感觉不错。
    这使我们兴奋不已，终于可以摆脱繁琐的嵌入式编程，快速地开发应用系统了。于是我们决定投人更大了力量来开发更加完美的饼干系统。
我们选择了更高的速率-100M以太网，实验了各种模块连接的方式。
当我们将饼干系统演示给一个资深的自动控制系统公司的老总看时，他提出了自己的担心”大多数自动控制的工程师习惯于梯形图，流程图这样的图形化编程，虽然javascript比较简单，但是他们依然不熟悉语言编程“。
      于是我们又开始大量地研究了图形程序设计技术和现有的编程环境。最出名的要数NI的LabView，比较和饼干系统接近的是IBM的 NODE-RED。
Labview 是一个相对完善的图形编程环境，不过它主要针对NI的硬件。而且我们决定它过度地“图形化”了，写一个简单i=i+1;都需要复杂的图形。




