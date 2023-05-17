# STARSET 歌詞翻譯集

## 使用許可
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1">
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/">若無特別聲明，<a property="dct:title" rel="cc:attributionURL" href="https://git.owu.one/starset-mirror/starset-lyrics">STARSET歌詞翻譯集</a> 由 <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://mirror.starset.fans">STARSET Mirror</a> 以 <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0</a> 協議及<a href="#附加條款">附加條款</a>授權。</p> 

### 附加條款
- STARSET Mirror 及翻譯作者（個人）保留將其自己創作的翻譯以任意其他協議或條款重新分發的權利。
- STARSET Mirror 保留追加、刪除和修改附加條款的權利。

### 例外情況
- 此儲存庫列出的英文歌詞僅供參考對照。原歌詞版權屬於其對應的創作者和版權持有者。

## 格式支持
### 檔案格式
- 所有歌詞與歌詞翻譯均採用`UTF-8`編碼的`LRC`格式。
- 時間戳精度為毫秒。
- 歌詞和翻譯不含空行。
- 格式範例：
  ```lrc
  [ti: 歌曲標題]
  [ar: 歌手名稱]
  [al: 專輯名稱]
  [by: 翻譯作者（如有）]
  [00:01.386] 第一句
  [00:08.523] 第二句
  [00:16.337] 第三句
  ```

### 命名格式
- 路徑結構：`/語言代碼/專輯名稱/兩位數序號-歌曲名(-翻譯作者).lrc`
- `翻譯作者`是可選項，英語歌詞和其它語言的默認譯本不包含此部分。

## 翻譯語言支持
- [x] [简体中文](./zh-CN)
- [x] [繁體中文](./zh-TW)

每個語種的歌詞可能含有多個譯本。此時譯本中的一個會被選為默認譯本。

## 默認譯本

默認譯本是現有歌詞譯本中較符合下述要求的譯本：
- 翻譯準確、生動，符合“信、達、雅”的翻譯原則
- 翻譯貼合STARSET世界觀

## 完善儲存庫內容
- 你可以透過以下任意方式提交新譯本：
  - [派生](https://git.owu.one/repo/fork/13)你自己的倉庫，按[格式支持](#格式支持)中的要求添加對應的文件，然後發起合併請求（Pull Request）。
  - 創建[新工單](https://git.owu.one/starset-mirror/starset-lyrics/issues)
  - 通過[Discord](https://discord.gg/zhEqePWneb)、[信箱](mailto:mirror@starset.fans)或STARSET_Mirror列出的其它聯絡方式聯繫STARSET_Mirror。
- 如果你希望更改默認譯本，請提交[新工單](https://git.owu.one/starset-mirror/starset-lyrics/issues)
