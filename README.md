# 冬夜星尘圣诞树 · 3D 互动惊喜 / Winter Night Stardust Christmas Tree

▶ **Live demo（在线打开就能玩）：https://sophielee-super.github.io/winter-star-christmas-tree/**

一棵长在冬夜里的 3D 圣诞树：圣诞老人乘着雪橇掠过月亮，把四份礼物洒落在树下，点开每一份，都是一份小惊喜。

A 3D Christmas tree on a winter night: Santa's sleigh crosses the moon and drops four gifts under the tree — tap each one for a surprise.

**双语切换 / Bilingual:** 页面左上角有「中文 / EN」按钮，一键切换整个页面（标题、提示、音乐按钮与四份礼物内容）。The 中文 / EN button in the top-left corner switches the whole page — title, hints, music button and all four gift surprises — between Chinese and English.

V2 是一次完整的视觉重建 —— 「电影感冬夜」：树有了真实的松树身形，装饰球是玻璃与金属的真实球体，圣诞老人是掠过月亮的剪影，整个界面统一为象牙纸面与金色的圣诞明信片风格。

## 玩法 / How to play

- **拖动**画面，旋转 3D 视角 / Drag to rotate the 3D view
- 等圣诞老人派送完礼物，**点击树下的礼盒**拆开惊喜 / Tap a gift under the tree:
  1. 圣诞来信 / Christmas letter
  2. 冬日暖心约定兑换券（可点击盖章领取）/ Winter feast voucher (tap to stamp & claim)
  3. 冬夜拍立得相册（可切换三张）/ Polaroid album (3 cards)
  4. 圣诞幸运签（可抽四支）/ Fortune slips (4 fortunes)
- **点击树顶的星星**，彩灯换上低调宝石色（彩蛋）/ Tap the star for the jewel-tone easter egg
- 右上角按钮开启 **Jingle Bells 圣诞音乐** / MUSIC button (top right) plays a Jingle Bells music box

## V2 视觉设计

- **一个色彩系统**：墨蓝冬夜、松绿、香槟金、奶油白，蔓越莓红只出现在礼盒上
- **真实树身**：不透明深松绿实体树芯打底，针叶内深、中翠、仅梢尖带霜白；发光只留给灯串、星星、月亮与火花
- **真实装饰球**：亮金、浅金、雾粉玻璃、冰蓝玻璃、哑光蔓越莓、霜白六种材质，大小三档、疏密不均
- **电影感场景**：实心月亮与双层光晕、带闪粉的蓝白雪地、树下金色光池、远景松树剪影、三层落雪、暗角与胶片颗粒、顶部松枝画框
- **剪影圣诞老人**：黑色剪影带着一盏暖灯笼与红鼻子驯鹿掠过月亮，洒下金色星尘
- **统一界面**：衬线标题（Merry Christmas + 金线 + 冬夜星尘）、无 emoji 的玻璃按钮、四个弹窗共用象牙纸面 + 金色顶边设计

## 技术 / Tech

- 单文件 HTML，Three.js（CDN）3D 场景 / Single-file HTML, Three.js via CDN
- Web Audio API 合成的铃儿响叮当旋律 / Web Audio Jingle Bells music box
- 无需构建，浏览器直接打开 `index.html` 即可；GitHub Pages 部署自 `main` 分支根目录

## 版本 / Versions

- **v2.1.0** — 双语切换：一个页面，中文 / English 一键切换（当前版本）
- **v2.0.0** — 电影感冬夜视觉重建
- **v1.0.0** — 初版：粒子圣诞树 + 发光雪橇派送

详见 [CHANGELOG](CHANGELOG.md)；旧版本可在 Releases 中下载。
