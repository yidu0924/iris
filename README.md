#  Iris
我是Iris。目前是单人款的客制化-储存bot。

## 功能介绍
目前我们使用Chain of Thought(CoT）和reflection进行prompt的调整
###
-**Chain of Thought**（
CoT，思维链）是一种推理方法，用于帮助人类或人工智能逐步解决问题。通过将复杂问题分解为一系列较小的步骤，思维链使每个步骤都建立在前一步的基础上，从而更容易理解和解决问题。这种方法在自然语言处理（NLP）中尤为重要，通过引导模型逐步推理，可以生成更连贯和逻辑的回答。例如，在回答复杂问题时，思维链可以帮助模型逐步分析和推理，最终给出准确的答案。
###
-**Reflection**
是一种通过回顾和修正模型生成的初始响应来提高响应质量的方法。这种方法鼓励模型在生成初始回答后，重新审视并改进其答案，类似于人类在做决定或解决问题时的自我反思过程。

示例：

问题：如果有三个苹果，给了两个朋友每人一个，还剩下几个？

初始回答：如果有三个苹果，给了两个朋友每人一个，还剩下一个苹果。

反思过程：

	1.	回顾：我一开始的回答是“还剩下一个苹果”。
	2.	检查逻辑：三个苹果减去两个朋友每人一个，的确是一个苹果。
	3.	确认或修正：答案是正确的，剩下一个苹果。


### 当前功能
- **客制化定制**：通过prompt实现个性化设置，满足不同用户的需求。
- **储存bot**：可以保存您的定制设置，方便下次使用。

### 未来功能（完全体）
- **个人账号**：支持创建和管理个人账户，提升个性化体验。
- **社区交流**：加入社区交流功能，让用户之间可以分享经验和交流心得。
- **微调功能**：支持微调功能，提升模型的定制化能力。（需要服务器支持）


## 参考文献

- Xavier Amatrain, "Prompt Design and Engineering: Introduction and Advanced Methods" https://doi.org/10.48550/arXiv.2401.14423
- 感谢ChatGPT-Assistant提供的模板！https://github.com/PierXuY/ChatGPT-Assistant.git

