专为中度至中深烘焙咖啡豆设计，目标是在尽量减少深烘焙豆常见的过度萃取的同时，优化萃取的均匀度。这是通过在萃取过程中将压力目标过渡到流量目标来实现的。

[SproFiler.io 萃取示例](https://sprofiler.io/shot/9fde95db-e383-45e3-a8f2-577e7c68aedf)

**冲煮准备：**
- 标准 20 克粉碗（不是高萃取 HE 粉碗）
- 19 克粉（大约 18-20 克应该都可以工作；根据需要调整基于重量停止的数值）

**主要目标：**
- 预浸泡 (PI)：由流量驱动，直至达到 2 bar
- 浸泡 (Soak)：短暂的浸泡以避免过度萃取，根据重量和压力下降的情况在 6 秒或更短时间内进行过渡
- 萃取：在 5 秒内爬升到 9 bar，然后在 4 秒内降低 1 bar，接着随着粉饼研磨度允许的情况过渡到由流量定义的曲线（压力应该逐渐下降）。10 秒后，或者如果压力下降 3 bar，流量将会增加以完成萃取。
- 重量：38 克（基于重量停止），1:2 的粉液比

**注意事项：**
- 预设了一些“挽救萃取”的过渡参数（例如，在预浸泡和/或浸泡期间如果杯中有一两克液体，会将配置文件推进到萃取阶段）。如果跳过了某个阶段或时间较短，可能是触发了其中一个条件。v1.5 增加了一个初始阶段，这样即使错过了压力释放，萃取也能照常运行。
- 对于某些咖啡豆，9-8 bar 会导致超出预期的油脂（crema）；在这种情况下，将萃取压力限制降低 1 bar 可能会有所帮助。
- 可以在 [Discord](https://discord.com/channels/890339612441063494/1251242799995556002) 找到一个预制的 LMD 8-7 以及更多参数调试指导。

---
*Original text:*
Designed for medium to medium-dark beans, the goal is to optimize for even extraction while minimizing the overextraction that can be common with darker beans. This is done by transitioning from a pressure target to a flow target during extraction. 

[SproFiler.io example shot](https://sprofiler.io/shot/9fde95db-e383-45e3-a8f2-577e7c68aedf)

**Shot Prep:**  
- standard 20 g basket (not HE)
- 19 g (should work from ~18-20 g; adjust stop-on-weight as needed)

**Main targets:**  
- PI: Flow driven until 2 bar
- Soak: Short soak to not over-extract, transitions after 6 sec or less based on weight & pressure drop
- Extraction: Climb to 9 bar over 5 sec, decrease 1 bar over 4 sec, then transition to flow defined profile as the puck grind allows (pressure should ramp down). After 10 seconds, or if pressure drops 3 bar, the flow increases to finish the shot. 
- Weight: 38 g stop-on-weight, 1:2 ratio 

**Notes:**  
- There are some "save the shot" transition parameters defined (e.g. a gram or two in the cup during PI and/or Soak will move the profile on to extraction). If a phase is skipped or short one of those was likely triggered. v1.5 adds an initial phase so that the shot will run even if pressure release was missed. 
- The 9-8 bar results in more crema than desired with some beans; in that case bumping extraction pressure limits down 1 bar can help. 
- A pre-made LMD 8-7 and more dialing guidance can be found on [Discord](https://discord.com/channels/890339612441063494/1251242799995556002)