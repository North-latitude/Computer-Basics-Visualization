## 1. 项目背景
在计算机网络通信中，数据传输容易受到干扰发生比特翻转。本项目通过可视化的方式，演示字符如何转换为ASCII二进制，并通过奇偶校验检测传输错误。

## 2. 项目目标
- 输入任意文本，转换为带校验位的8位二进制数据帧。
- 模拟数据在传输过程中发生比特翻转（噪声干扰）。
- 接收端进行奇偶校验，并报告数据是否损坏。

## 3. 技术栈与工具
- 编程语言：Python
- 界面库：Tkinter
- 版本控制：Git + GitHub
- 开发环境：VS Code
- 编程范式：Vibe Coding (AI辅助开发)

## 4. 核心原理
**奇偶校验位**的计算方式：统计7位ASCII码中`1`的个数。
- 偶校验：使总`1`的个数为偶数。
- 奇校验：使总`1`的个数为奇数。
接收端重新计算校验位，若与收到的校验位不一致，说明数据在传输中发生了损坏。

## 5. 团队分工
| 姓名 | 角色 | 负责内容 |
| :--- | :--- | :--- |
| 高郑豪 | 组长/核心开发 | 编写 core_logic.py 核心算法，Git仓库管理，代码审查 |
| （填队友A） | 文档撰写 | 完善Markdown文档，绘制流程图 |
| （填队友B） | UI开发 | 使用AI生成Tkinter界面 main.py |
| （填队友C） | 测试与日志 | 测试程序Bug，记录AI_Prompts_Log.md |

## 6. 参考图片
![ppp帧格式](https://raw.githubusercontent.com/North-latitude/Computer-Basics-Visualization/refs/heads/main/ppp_frame.png)

## 7. 开源协议
本项目采用 MIT License 开源协议。
