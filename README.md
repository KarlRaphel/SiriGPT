# 手把手教你免费将OpenAI和Gemini接入Siri

**完全免费获取 | 轻松自定义接口、密钥、模型、提示词 ｜ 支持正确的上下文输入 | 语音提示和输入**

### 特点
现有的快捷指令通常都涉及非常复杂的字典、列表。此脚本直接以文本形式构建json请求体，并且正确构建了上下文，让你的第二个问题可以承接第一个。

## 快速开始

https://www.icloud.com/shortcuts/8e99a6cfb2094998973313618f9e46e2

通过这个链接可以将我写的快捷指令添加到你的手机  
修改其中的接口、密钥、模型、提示词为你自己的（脚本中以硅基流动为例，如果你也使用，可以只修改密钥）  
**如果你没有这些信息，可以参考第二步教你如何获取一个**  

接着，修改快捷指令的名字，例如改成“那我问你”  
这样，就可以和Siri说“Siri，那我问你”唤醒该快捷指令  
当Siri和你说完开场白（默认设定为“你好！我是DeepSeek”），你就可以对它进行提问了  
当Siri回答完以后，会提示你“请继续提问”，你可以继续进行提问，Siri会记得你刚才问了它什么。  
你也可以将该快捷指令添加到主屏幕，这样就可以快速询问一些问题。  

## 如何获取一个密钥？

你可以在硅基流动注册一个账号，新账户会赠送一些使用额度。你也可以通过把模型设置为没那么智能的 `Qwen/Qwen2.5-7B-Instruct` 来永久免费使用  
该快捷指令支持所有标准 OpenAI 的请求，你也可以自定义接口、密钥、模型， 例如字节火山、阿里云百炼，甚至自己部署ollama等。  

## 感觉还不错？

https://www.icloud.com/shortcuts/09d8a61fec7d4dcb88c16c2c0786b6b8

这是一个 Gemini 版本的快捷指令，你可以自己部署反代服务器，从而通过Siri快速与Gemini对话！

<img src="alipay.JPG" width="250">
