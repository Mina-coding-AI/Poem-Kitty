# 🐱 小猫的奇幻旅程 - 唐诗朗诵游戏
# Kitten's Magical Journey - Tang Poetry Recitation Game

一个可爱的互动网页游戏，让小猫咪用童声为你朗读经典唐诗！
An adorable interactive web game where a cute kitten recites classic Tang poetry with a child-like voice!

## 🌟 特色功能 (Features)

- 🐱 **可爱小猫互动** - 点击小猫触发朗诵
- 🎵 **TTSMaker童声** - 真实的儿童声音，不是机器音
- 📚 **12首经典唐诗** - 包含《静夜思》《春晓》等名作
- 📱 **响应式设计** - 完美适配手机、平板、电脑
- 🎨 **温馨界面** - 奶黄色渐变背景，视觉舒适
- 🔊 **音效丰富** - 猫叫声 + 童声朗诵的完美组合

## 🎮 如何玩 (How to Play)

1. 打开网页，看到小猫咪在可爱地左右摇头
2. 点击小猫咪
3. 听到"喵~"一声后，小猫会随机朗诵一首唐诗
4. 右侧会显示完整的诗歌文字
5. 朗诵结束后，小猫继续摇头等待下一次点击

## 📁 文件结构 (File Structure)

```
kitten-poetry-game/
├── index.html              # 主游戏文件
├── kitten2.png            # 小猫图片 (透明PNG)
├── kitten.jpg             # 备用图片
├── audio/                 # TTSMaker音频文件夹
│   ├── poem_1_静夜思.mp3.mp3
│   ├── poem_2_春晓.mp3.mp3
│   ├── poem_3_登鹳雀楼.mp3.mp3
│   ├── poem_4_相思.mp3.mp3
│   ├── poem_5_江雪.mp3.mp3
│   ├── poem_6_悯农.mp3.mp3
│   ├── poem_7_回乡偶书.mp3.mp3
│   ├── poem_8_咏鹅.mp3.mp3
│   ├── poem_9_草.mp3.mp3
│   ├── poem_10_山行.mp3.mp3
│   ├── poem_11_枫桥夜泊.mp3.mp3
│   └── poem_12_望庐山瀑布.mp3.mp3
├── test-audio.html        # 音频测试工具
├── DEPLOYMENT-GUIDE.md    # 部署指南
└── README.md              # 本文件
```

## 🚀 快速部署 (Quick Deployment)

### 方法1: GitHub Pages (推荐)
1. 将所有文件上传到GitHub仓库
2. 在仓库设置中启用GitHub Pages
3. 获得类似 `https://yourusername.github.io/repo-name/` 的链接

### 方法2: Netlify
1. 将整个文件夹拖放到 Netlify.com
2. 立即获得在线链接

### 方法3: Vercel
1. 连接GitHub仓库到Vercel
2. 自动部署并获得链接

**详细部署步骤请参考 [DEPLOYMENT-GUIDE.md](DEPLOYMENT-GUIDE.md)**

## 🎭 包含的唐诗 (Included Tang Poems)

1. **静夜思** - 李白
2. **春晓** - 孟浩然  
3. **登鹳雀楼** - 王之涣
4. **相思** - 王维
5. **江雪** - 柳宗元
6. **悯农** - 李绅
7. **回乡偶书** - 贺知章
8. **咏鹅** - 骆宾王
9. **草** - 白居易
10. **山行** - 杜牧
11. **枫桥夜泊** - 张继
12. **望庐山瀑布** - 李白

## 🎵 音频技术 (Audio Technology)

- **优先使用TTSMaker音频** - 真实儿童声音
- **智能降级** - 如果TTSMaker音频不可用，自动切换到浏览器TTS
- **完美兼容** - 支持所有现代浏览器
- **离线友好** - 音频文件本地存储，加载快速

## 📱 浏览器支持 (Browser Support)

- ✅ Chrome/Chromium (推荐)
- ✅ Safari 
- ✅ Firefox
- ✅ Edge
- ✅ 移动端浏览器

## 🎨 设计亮点 (Design Highlights)

- **温馨色调** - 奶黄色(#FFF8DC)到古白色(#F5E6D3)渐变
- **动画效果** - 小猫左右转头动画(rotateY -15°到15°)
- **响应式布局** - 使用50vmin确保各设备完美显示
- **用户体验** - 点击提示、加载状态、错误处理

## 🧪 测试工具 (Testing Tools)

使用 `test-audio.html` 来测试所有TTSMaker音频文件是否正常工作：
1. 在浏览器中打开 `test-audio.html`
2. 逐个测试每个音频文件
3. 确保所有文件都能正常播放

## 🌍 分享给世界 (Share with the World)

一旦部署完成，您就可以：
- 📧 通过邮件分享链接
- 📱 在社交媒体上分享
- 👨‍👩‍👧‍👦 给家人朋友分享
- 🏫 在教学中使用

## 💝 致谢 (Acknowledgments)

- **TTSMaker.cn** - 提供高质量童声语音合成
- **中华古典文学** - 经典唐诗的永恒魅力
- **所有诗人** - 李白、杜甫、王维等诗歌大师

---

**🎉 享受您的可爱小猫唐诗游戏吧！让文化传承变得更加有趣！**

Made with ❤️ for poetry lovers and cute cat enthusiasts!