## 生日快乐

> <b>修改config.js的配置就可以为您心爱的人做一个超具创意的网页生日快乐呀,喜欢的话fork or star一下呗~</b>

<img src="https://github.com/AJLoveChina/loveBalloon/blob/master/static/github-star.png" />

## TODO
* [x] 每行祝福文字可以配一张图片
* [ ] 配图支持旋转

### config.js 说明
> 温馨提示: 每句话丶每个图片地址丶每个按钮文字的那一行，最后都要以**英文逗号**结尾哦！
```text
var config = {
    // 句子的长度可以任意， 你可以写十句话， 二十句话都可以
    // 每句话尽量不要超过15个字,不然展示效果可能不太好
    texts: [
        "嘿 你好吖 cool女孩",      //这里,每句话结尾的最后一个逗号必须是英文的哦!! 很重要哦!!
        "记得你说过",  // 同上...
        "一般你都提前一天和妈妈一块过",
        "那我就抓住13号的最后一分钟",
        "和14号的第一分钟 来给你祝福",
        "生日快乐",
        "生日快乐丫 我梦里的女孩",
        "还记得你放过的那个孔明灯吗",
        "它挂树枝上了",
        "你焦急 害怕",
        "但最后它还是起来了",
        "载满那些希冀与期望",
        "升的更高 更远...",
        "过程曲折",
        "但最后都是会变好的",
        "其实我一直想问",
        "你羡慕她们吗",
        "我不知道 答案",
        "但我知道的是",
        "有一天",
        "你会穿着洁白的婚纱",
        "变成最美的新娘",
        "那一天 你笑得比谁都开心",
        "那一天 你也会流泪",
        "但那是快乐 幸福的眼泪",
        "那是我的一个梦",
        "未来的时间",
        "我会努力的创造",
        "我和你之间",
        "人生轨迹的交集",
        "因为我相信",
        "那是属于我们的梦",
        "对了，",
        "天凉了 记得添衣",
        "热水泡脚挺好的",
        "不要一直压力那么大",
        "做一个开心 快乐的",
        "小可爱",
        "啾咪 hiahiahia",
        "其实我想",
        "我想陪你一直走下去",
        "直到你不需要我的那一天",
        "生日快乐!(^O^)y",
        "梦里的女孩！",
    ],
    /**
     * imgs 可以不填, 但是如果要填写的话必须遵循下面的格式
     * "对应上面的文字, 要完全一样" : "图片地址, 可以把图片放在imgs文件夹中"
     * 例如
     * "心爱的小可爱": "./imgs/xiaokeai.jpg"
     *
     * 如果不要图片的话, 直接在每行开头写两个斜杠注释即可, 例如下面的 "今天是你的生日" 的图片就不会展示了:)
     * Tip: 图片最好用正方形or接近正方形, 看起来效果更好
     */
    imgs: {
        "心爱的小可爱": "./imgs/xiaokeai.png",
        // "今天是你的生日": "./imgs/birthday.jpg",
    },
    // 按钮文字描述, 以下是默认的按钮文字，英文的，您可以改成你喜欢的文字
    desc: {
        turn_on: "开始",
        play: "音乐",
        bannar_coming: "颜色",
        balloons_flying: "好像少点东西",
        cake_fadein: "蛋糕？",
        light_candle: "蜡烛？",
        wish_message: "生日快乐",
        story: "A MESSAGE FOR YOU",
    }
};
```


## 截图演示
<img src="./assets/birthday-demo2.gif"/>

## 知乎使用教程
[https://zhuanlan.zhihu.com/p/85899661](https://zhuanlan.zhihu.com/p/85899661)

## 结尾
喜欢的话关注一下[霸都丶傲天](https://github.com/ajlovechina)呗~  \
定期更新一下爱情网页模板,简历模板,知识笔记,PDF书籍,原创深度技术分享等 :heart:

* 知乎:[霸都丶傲天](https://www.zhihu.com/people/AJLoveChina)
* Github:[霸都丶傲天](https://github.com/ajlovechina)

## QA
> 如何修改音乐？
> 
> 回答：将你自己的mp3音乐文件覆盖`assets`目录下面的`hbd.mp3`, 記住覆蓋后名字要完全一樣哦！


## 链接
* [第一期:爱情树 🌴将相爱的时刻永远珍藏 （微信，QQ可完美查看）](https://github.com/AJLoveChina/LoveTree)
* [第二期: :cake:改改数据,为心爱的人做一个超具创意的网页生日祝福吧~ (生日快乐)](https://github.com/AJLoveChina/birthday)
* [第三期: :balloon:塞纳河畔，左岸的咖啡。告白气球，飞入我的心扉。](https://github.com/AJLoveChina/loveBalloon)
