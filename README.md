![Uploading IDE安装素材.png…]()
主页｜🛠 插件 VS Code, Jetbrains｜🤗 模型下载｜📄 论文｜👋 加入微信开发者交流群

Read this in English
日本語で読む
Lire en Français

CodeGeeX2: 更强大的多语言代码生成模型
CodeGeeX2 是多语言代码生成模型 CodeGeeX (KDD’23) 的第二代模型。不同于一代 CodeGeeX（完全在国产华为昇腾芯片平台训练） ，CodeGeeX2 是基于 ChatGLM2 架构加入代码预训练实现，得益于 ChatGLM2 的更优性能，CodeGeeX2 在多项指标上取得性能提升（+107% > CodeGeeX；仅60亿参数即超过150亿参数的 StarCoder-15B 近10%），更多特性包括：

更强大的代码能力：基于 ChatGLM2-6B 基座语言模型，CodeGeeX2-6B 进一步经过了 600B 代码数据预训练，相比一代模型，在代码能力上全面提升，HumanEval-X 评测集的六种编程语言均大幅提升 (Python +57%, C++ +71%, Java +54%, JavaScript +83%, Go +56%, Rust +321%)，在Python上达到 35.9% 的 Pass@1 一次通过率，超越规模更大的 StarCoder-15B。
更优秀的模型特性：继承 ChatGLM2-6B 模型特性，CodeGeeX2-6B 更好支持中英文输入，支持最大 8192 序列长度，推理速度较一代 CodeGeeX-13B 大幅提升，量化后仅需6GB显存即可运行，支持轻量级本地化部署。
更全面的AI编程助手：CodeGeeX插件（VS Code, Jetbrains）后端升级，支持超过100种编程语言，新增上下文补全、跨文件补全等实用功能。结合 Ask CodeGeeX 交互式AI编程助手，支持中英文对话解决各种编程问题，包括且不限于代码解释、代码翻译、代码纠错、文档生成等，帮助程序员更高效开发。
更开放的协议：CodeGeeX2-6B 权重对学术研究完全开放，填写登
