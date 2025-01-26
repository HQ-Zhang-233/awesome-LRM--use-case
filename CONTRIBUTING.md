# Contributing to Awesome LRM Use Cases

欢迎来到 `awesome-lrm-use-case` 仓库！ 我们非常感谢你对这个精选的大型推理模型 (LRM) 使用案例列表的贡献。 你的贡献将帮助更多的人了解和应用强大的 LRM 模型。

## 如何贡献

我们鼓励各种形式的贡献，包括但不限于：

* **添加新的 LRM 使用案例:**  发现了一个很棒的 LRM 应用案例？ 请提交给我们！
* **改进现有案例描述:**  如果你发现现有案例的描述不够清晰或可以改进的地方，欢迎提出修改建议。
* **修复链接错误:**  如果你发现列表中的链接失效，请告知我们或提交 Pull Request 进行修复。
* **改进文档:**  如果你发现 `README.md` 或 `CONTRIBUTING.md` 文档可以改进的地方，例如更清晰的说明、更好的组织结构等，欢迎提出建议或直接修改。

以下是详细的贡献步骤：

1. **Fork 仓库:**  点击 GitHub 页面右上角的 "Fork" 按钮，将 `awesome-lrm-use-case` 仓库 Fork 到你的 GitHub 账号下。

2. **克隆 Fork 后的仓库到本地:**
   打开你的终端 (Terminal 或 Command Prompt)，并使用 `git clone` 命令克隆你 Fork 后的仓库到本地：
   ```bash
   git clone https://github.com/<你的GitHub用户名>/awesome-lrm-use-case.git
   cd awesome-lrm-use-case
   ```
   （请将 `<你的GitHub用户名>` 替换成你的 GitHub 用户名）

3. **创建新的分支:**  为你本次的贡献创建一个新的分支。分支名称应该简洁明了，描述你的贡献内容，例如 `add-gemini-education-use-case` 或 `fix-broken-link-in-readme`。
   ```bash
   git checkout -b <你的分支名称>
   ```
   例如： `git checkout -b add-ollama-researcher-case`

4. **添加你的贡献:**
   * **修改 `README.md` 文件:** 这是添加新用例的主要文件。
      * 找到最合适的 **使用场景分类** (例如：内容创作、教育与学习、研究与分析等)。
      * 在该分类下，按照已有的格式添加新的 LRM 使用案例。

   * **用例条目格式:**  每个用例条目应遵循以下 Markdown 格式：
      ```markdown
      * **[案例名称](链接到案例)** - 简短而精炼的描述案例。 描述应突出案例的亮点、使用的 LRM 模型 (如果明确) 以及应用场景的特点。  尽量用一句话或两句话概括。
      ```
      **示例:**
      ```markdown
      * **[Ollama Deep Researcher](https://github.com/langchain-ai/ollama-deep-researcher)** - 给 DeepSeek R1 模型一个主题，观察它自主搜索网络、学习、反思并生成研究报告。 演示了 R1 模型在自动化研究和信息收集方面的潜力。
      ```

   * **确保你的贡献符合贡献准则 (见下一节)。**

5. **提交你的更改:**
   使用 `git add` 命令将你修改的文件添加到暂存区，然后使用 `git commit` 命令提交你的更改。  请使用 **清晰且有意义的提交信息**，简要描述你的贡献内容。
   ```bash
   git add README.md
   git commit -m "Add: Ollama Deep Researcher use case to Research & Analysis section"
   ```

6. **推送你的分支到 GitHub:**
   将你的本地分支推送到你 Fork 后的 GitHub 仓库。
   ```bash
   git push origin <你的分支名称>
   ```
   例如： `git push origin add-ollama-researcher-case`

7. **创建 Pull Request (PR):**
   * 访问你的 Fork 后的仓库页面 (`https://github.com/<你的GitHub用户名>/awesome-lrm-use-case`)。
   * GitHub 会在你推送分支后提示你创建一个 Pull Request，点击 "Compare & pull request" 按钮。
   * 填写 Pull Request 的标题和描述。
      * **标题:**  简明扼要地描述你的贡献，例如 "Add Ollama Deep Researcher use case" 或 "Fix broken link in Education section"。
      * **描述:**  更详细地说明你的贡献内容，例如案例的来源、特点，或者修复了哪个链接等。
   * 点击 "Create pull request" 按钮。

8. **等待审核:**  仓库维护者会审核你的 Pull Request。  请耐心等待，并及时回复维护者提出的任何问题或修改建议。  一旦你的 Pull Request 通过审核，你的贡献将被合并到主仓库中。

## 贡献准则

为了维护 `awesome-lrm-use-case` 列表的质量和价值，请在贡献时遵循以下准则：

* **相关性:**  贡献的案例必须与 **大型推理模型 (LRM)** 的实际应用相关。 我们关注的是利用 LRM 模型进行推理、理解、生成、解决问题等方面的用例。
* **高质量:**  请选择 **优秀、有价值、具有代表性** 的用例。  避免添加过于简单、不成熟或质量不高的案例。
* **描述清晰简洁:**  用例描述应 **简洁明了，突出案例的亮点和 LRM 模型的应用方式**。  避免长篇大论或过于技术化的描述。
* **链接有效性:**  请确保你提供的 **链接是有效的，并且指向高质量的资源** (例如：官方网站、GitHub 仓库、演示示例、博客文章、论文等)。
* **避免重复:**  在添加新用例之前，请先 **搜索列表，确保没有重复的案例**。 如果有相似的案例，请考虑是否你的案例有独特的价值或角度。
* **客观性:**  描述用例时，请尽量保持 **客观中立** 的态度，避免过度宣传或个人主观评价。
* **尊重开源协议:**  所有贡献都将被视为遵循本仓库的 [MIT License](LICENSE) 开源许可证。

**以下是一些不适合添加到列表中的例子：**

* 仅仅是 LRM 模型的简单介绍或评测文章，而没有实际的应用案例。
* 非常基础、没有实际应用价值的 Demo 或示例。
* 链接失效或指向低质量内容的资源。
* 与 LRM 模型推理能力无关的用例 (例如：仅仅是文本生成，但没有体现推理过程)。
* 商业广告或推广内容。

## 代码行为准则

我们希望 `awesome-lrm-use-case` 成为一个友好和包容的社区。  请在贡献和参与讨论时，保持尊重、友善和建设性的态度。  任何形式的不尊重、歧视或攻击性言论都是不允许的。

## 感谢你的贡献！

感谢你花时间为 `awesome-lrm-use-case` 做出贡献！ 你的努力将帮助更多人发现和利用大型推理模型的潜力。  我们期待你的精彩贡献！

如果你有任何疑问或建议，欢迎提出 Issue 或在 Pull Request 中与我们交流。
