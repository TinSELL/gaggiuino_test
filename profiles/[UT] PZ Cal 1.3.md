实用配置 - PZ (Pump Zero) 校准

**设置：**
- 关闭 Brew/Temperature Delta（冲煮/温度温差）；保存
- 关闭 BT Scales（蓝牙秤）、HW Scales（硬件秤），开启 Forced Predictive（强制预测）；保存
- 可选：将 PZ Cal (PZ 校准) 设置为启动配置，这样锅炉在开机时不会加热
- 重启（否则 Brew Delta 会保持开启状态）
- 等待温度 <25 C
- 运行配置的前 5 秒以释放压力
- 运行配置的前 5 秒，并确认压力保持在 ≤0.1 bar。如有必要，请在测试前进行反冲洗、清洁并卸下分水网。

**测试：**
- 在秤上放置一个杯子并去皮
- 开始运行 PZ Cal，*此时不要放上杯子*
- 在初始 3 秒的出水后，擦拭分水网、接水盘，然后放上杯子。水流测试将在第 20 秒开始。
- 萃取结束后称量杯子+水的重量。目标重量是 100 g；如果重量超出，则调高 PZ 值；如果重量不足，则调低 PZ 值。
- 根据需要重复测试步骤

**重置：**
- 重置 Brew/Temperature Delta（冲煮/温度温差）；保存
- 开启所需的秤选项，关闭其他选项；保存
- 如果更改了启动配置，请重置
- 重启

---
*Original text:*
Utility profile - PZ Calibration

**Setup:**
- Turn off Brew/Temperature Delta; save
- Turn off BT Scales, HW Scales, turn on Forced Predictive; save
- Optional: set PZ Cal to the startup profile so boiler doesn't heat on boot
- Reboot (otherwise Brew Delta stays on)
- Wait for temp <25 C
- Run the first 5 seconds of the profile to clear pressure
- Run the first 5 seconds of the profile and verify pressure stays ≤0.1 bar. If necessary, backflush, clean, and remove shower screen for the test. 

**Test:**
- Tare a cup on a scale
- Start PZ Cal *without placing the cup*
- After initial 3 seconds of flow, wipe shower screen, drip tray, and then place the cup. The flow test will start at 20 sec.
- Weigh cup + water after the shot. Target is 100 g; adjust PZ up if weight is over and down if weight is under 
- Repeat test steps as needed

**Reset:**
- Reset Brew/Temperature Delta; save
- Turn on desired Scales option, turn off others; save
- Reset startup profile if changed
- Reboot