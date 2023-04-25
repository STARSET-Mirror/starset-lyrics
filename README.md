# STARSET 歌词翻译集

## 使用许可
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1">
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/">若无特别声明，<a property="dct:title" rel="cc:attributionURL" href="https://git.owu.one/starset-mirror/starset-lyrics">STARSET歌词翻译</a> 由 <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://mirror.starset.fans">STARSET Mirror</a> 以 <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0</a> 协议及<a href="#附加条款">附加条款</a>授权。</p> 

### 附加条款
- STARSET Mirror 及翻译作者（个人）保留将其自己创作的翻译以任意其他协议或条款重新分发的权利。
- STARSET Mirror 保留追加、删除和修改附加条款的权利。

### 例外情况
- 此存储库列出的英文歌词仅供参考对照。原歌词版权属于其对应的创作者和版权持有者。

## 格式支持
### 文件格式
- 所有歌词与歌词翻译均采用`UTF-8`编码的`LRC`格式。
- 时间戳精度为毫秒。
- 歌词和翻译不含空行。
- 格式示例：
  ```lrc
  [ti: 歌曲标题]
  [ar: 歌手名称]
  [al: 专辑名称]
  [by: 翻译作者（如有）]
  [00:01.386] 第一句
  [00:08.523] 第二句
  [00:16.337] 第三句
  ```

### 命名格式
- 路径结构：`/语言代码/专辑名称/两位数序号-歌曲名(-翻译作者).lrc`
- `翻译作者`是可选项，英语歌词和其它语言的默认译本不包含此部分。

## 翻译语言支持
- [x] [简体中文](./zh-CN)
- [ ] 繁體中文

每个语种的歌词可能含有多个译本。此时译本中的一个会被选为默认译本。

## 默认译本

默认译本是现有歌词译本中较符合下述要求的译本：
- 翻译准确、生动，符合“信、达、雅”的翻译原则
- 翻译贴合STARSET世界观

## 完善存储库内容
- 你可以通过以下任意方式提交新译本：
  - [派生](https://git.owu.one/repo/fork/13)你自己的仓库，按[格式支持](#格式支持)中的要求添加对应的文件，然后发起合并请求（Pull Request）。
  - 创建[新工单](https://git.owu.one/starset-mirror/starset-lyrics/issues)
  - 通过[QQ群](https://shang.qq.com/wpa/qunwpa?idkey=54df8ffb39619553024762b0aee78f1a584980c6fc5d4d6caa92831055959c3c)、[邮箱](mailto:mirror@starset.fans)或STARSET_Mirror列出的其它联系方式联系STARSET_Mirror。
- 如果你希望更改默认译本，请提交[新工单](https://git.owu.one/starset-mirror/starset-lyrics/issues)
