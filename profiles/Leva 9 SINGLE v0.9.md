*一个模拟弹簧拉杆机的配置文件*

真正的弹簧拉杆机的压力下降并不取决于经过的时间，而是取决于缸内排出的水量。
这个配置文件试图在 Gaggiuino 上模拟这种行为，方法是设置多个递增的压力阶段，将“泵水量”作为停止条件，从 9 bar 开始递减。

[原作者帖子可以在这里找到](https://discord.com/channels/890339612441063494/1326340673950973962/1326340673950973962)。

*预浸泡（阶段 1-3）：*

为了使该配置文件正常工作，在预浸泡结束时，冲煮头顶部的空间和粉饼应该完全饱和。
预浸泡以快速水流开始，并随着压力的升高而减慢。
最后一个阶段是 3 bar 的保持，在 7 秒后或杯中达到 10 克时停止。

*主要萃取（阶段 4 及以后）：*

所有阶段的“压力”和“泵水量”的组合定义了模拟拉杆机的“弹簧行为”和“气缸容量”。

萃取从上升到 9 bar 开始，并持续下降。
在达到 6 bar 后的输出重量应该在 20 克左右。
主要阶段的流量被限制在 1.5 ml/s，以防止“喷涌 (gushers)”。

可以使用不同的预浸泡、压力下降等参数。
请随意根据您的喜好更改此配置文件！

*__此配置文件极其依赖于计算出的“泵流量 (pump flow)”，因此 PZ 校准非常重要！__*

---
*Original text:*
*A profile that emulates a spring lever*

The pressure decline of a real spring lever machine is not dependent on elapsed time, but on the volume of water displaced inside the cylinder.
This profile tries to emulate this behaviour with Gaggiuino by setting up multiple incremental pressure phases with "water pumped" as stop conditions, declining from 9 bar.

[Original creator post can be found here](https://discord.com/channels/890339612441063494/1326340673950973962/1326340673950973962).

*Preinfusion (Phases 1-3):*

For the profile to work properly, the headspace and puck should be fully saturated at the end of preinfusion.
Preinfusion starts with fast flow and slows down as the pressure rises.
The last phase is a 3 bar hold, stopping either after 7 seconds or 10 grams in the cup.

*Main Extraction (Phases 4 onwards):*

The combination of "pressure" and "pumped water" of all phases defines the "spring behavior" and "cylinder capacity" of the simulated lever.

Extraction starts with a rise to 9 bar and continues to decline.
The output weight after reaching 6 bar should be about 20 grams.
The flow in the main phases is limited to 1.5 ml/s to prevent "gushers".

Different preinfusions, pressure declines, etc. are possible.
Feel free to change the profile to your liking! 

*__This profile is extremely dependent on the calculated "pump flow", so PZ calibration is important!__*