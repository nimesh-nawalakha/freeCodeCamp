---
id: 587d7dbc367417b2b2512bae
title: 構建一臺鼓式機器
challengeType: 3
forumTopicId: 301370
dashedName: build-a-drum-machine
---

# --description--

**Objective:** Build an app that is functionally similar to this: <a href="https://drum-machine.freecodecamp.rocks/" target="_blank" rel="noopener noreferrer nofollow">https://drum-machine.freecodecamp.rocks/</a>.

完成以下需求，並且通過所有測試。 可以使用你需要的任何庫或 API。 賦予它你自己的個人風格。

可以使用 HTML、JavaScript、CSS、Bootstrap、SASS、React、Redux、jQuery 來完成這個挑戰。 但鑑於這個章節的學習內容與前端框架相關，推薦使用一款前端框架（比如 React）來完成這個挑戰。 不推薦使用前面沒有提到的技術，否則風險自擔。 我們有計劃新增其他前端框架課程，例如 Angular 和 Vue，不過目前還沒有這些內容。 我們會接受並嘗試修復你在使用推薦技術棧創建項目時報告的問題。 編碼愉快！

**需求 1：** 應該可以看到一個具有 `id="drum-machine"` 屬性的外層容器，該容器包含了其它所有元素。

**需求 2：** 在具有 `#drum-machine` 屬性的元素內，應該能看到一個具有 `id="display"` 屬性的元素。

**需求 3：** 在具有 `#drum-machine` 屬性的元素內，應該能看到 9 個可以點擊的鼓墊元素，且每個鼓墊元素都應該有一個值爲 `drum-pad` 的 class 屬性， 一個用於描述觸發鼓墊音頻片段的特殊 id，以及以下鍵值之一的文本內容：`Q`、`W`、`E`、`A`、`S`、`D`、`Z`、`X`、`C`。 這些鼓墊必須按照以上順序排列。

**需求 4：** 在每一個具有 `.drum-pad` 屬性的元素內，應該有一個具有指向音頻片段地址的 `src` 屬性的 HTML5 `audio` 元素，一個值爲 `clip` 的 class 屬性，以及一個 id 屬性，它的值應該是其父元素 `.drum-pad` 的文本內容（例如 `id="Q"`、`id="W"`、`id="E"` 等等）。

**需求 5：** 當點擊一個具有 `.drum-pad` 屬性的元素時，應該觸發它的子元素 `audio` 包含的音頻片段。

**需求 6：** 當按下每一個 `.drum-pad` 元素的關聯鍵時，應該觸發其子元素 `audio` 包含的音頻片段（例如：按下 `Q` 鍵應該觸發包含字符串 `Q` 的鼓墊，按下 `W` 鍵應該觸發包含字符串 `W` 的鼓墊等等）。

**需求 7：** 當觸發一個具有 `.drum-pad` 屬性的元素時，`#display` 元素內應該展示這個觸發元素關聯音頻片段的描述字符串（每一個字符串都應該是獨一無二的）。

以下是一些可用於鼓機的音頻樣本：

- [Heater 1](https://s3.amazonaws.com/freecodecamp/drums/Heater-1.mp3)
- [Heater 2](https://s3.amazonaws.com/freecodecamp/drums/Heater-2.mp3)
- [Heater 3](https://s3.amazonaws.com/freecodecamp/drums/Heater-3.mp3)
- [Heater 4](https://s3.amazonaws.com/freecodecamp/drums/Heater-4_1.mp3)
- [Clap](https://s3.amazonaws.com/freecodecamp/drums/Heater-6.mp3)
- [Open-HH](https://s3.amazonaws.com/freecodecamp/drums/Dsc_Oh.mp3)
- [Kick-n'-Hat](https://s3.amazonaws.com/freecodecamp/drums/Kick_n_Hat.mp3)
- [Kick](https://s3.amazonaws.com/freecodecamp/drums/RP4_KICK_1.mp3)
- [Closed-HH](https://s3.amazonaws.com/freecodecamp/drums/Cev_H2.mp3)

你可以<a href='https://codepen.io/pen?template=MJjpwO' target='_blank' rel="noopener noreferrer nofollow">使用 CodePen 模版</a>創建你的新項目，點擊 `Save` 即可創建你的新項目。 或者你可以在任何你喜歡的環境中使用以下 CDN 鏈接來運行測試：`https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js`。

當你完成了本項目，並且項目通過所有測試，請提交項目的 URL。

# --solutions--

```js
// solution required
```
