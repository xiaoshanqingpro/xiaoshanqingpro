# 你好，我是 xiaoshanqingpro

林学背景，做"把真实需求做成能跑、能验证的系统"这件事。兴趣在**图像分割**、**复杂系统仿真**和**桌面自动化**——共同点是：都要跟真实数据、真实软件的限制搏斗。

## 代表仓库

| 仓库 | 是什么 | 有意思的点 |
|---|---|---|
| [root-segmentation](https://github.com/xiaoshanqingpro/root-segmentation) | 根系扫描图像分割：CV 规则管线 + U-Net，交付 WinRHIZO 可直接测量的干净根图 | 冻结评估协议 + 可执行的数据泄漏守卫；三臂无泄漏对照实验；读 PE 头定位 32 位软件 2 GB OOM |
| [boids-predation-sim](https://github.com/xiaoshanqingpro/boids-predation-sim) | 单文件零依赖的鸟群涌现 × 猛禽掠食仿真 | 拓扑 boids / 隼链式攻击 / 鹰 Q-learning / 雁隼 UCB1；WebGPU 计算后端与 CPU 位级对拍；守恒线是可执行断言 |
| [autorhizo](https://github.com/xiaoshanqingpro/autorhizo) | WinRHIZO 半自动批量分析工具 | 对一个拒绝自动化的商业软件做 RPA：ROI 检测、画框、缩放、断点续跑；把"做不到的部分"写清楚 |
| [tree-assistant](https://github.com/xiaoshanqingpro/tree-assistant) | 树木学期末复习 PWA 闪卡（239 题 / 36 科） | 数据与模板分离的可复现构建；离线优先的单文件交付 |

## 我信的东西

- **先测量，再优化**：每个参数改动都要有 A/B 数据和时间/显存代价，否则不写进代码。
- **诚实清单**：README 里的"已知问题"应该比"成果"长。
- **能复现才算做完**：要么一条命令跑通，要么写清为什么跑不通。

## 技术栈

`Python`（OpenCV / PyTorch / scikit-image / pandas） · `JavaScript`（WebGPU / Canvas / Node 无头测试） · `Git` · 一点 `Windows` 系统层（Win32 / UI Automation / PE 头 / TIFF 标签）

---

持续把项目往这里搬：能跑、能验证、能被别人接手。