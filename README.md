# slide

> 作者：李成龙
> 贡献者：[点击查看详细信息](#version)
> 版本信息：[点击查看详细信息](#version)
> 类型：js模块
> 依赖模块：无
> 依赖插件：jquery
> 依赖雪碧图：无
> 文档：[API](#api)

使用方法

```js
/**
* 以默认配置启动分类模块
**/
runImg.run()

/**
* 配置并启动分类模块
**/
runImg.setting = {
    el:'#banner-box',
    imgBox: '.img-box',
    times: 5000,
    slidebtn:'#banner-right-textButton',
    active:'active'
};
runImg.run();
```

# version

| 版本 | 备注 | 贡献者 | 
| :--: | :--: | :--: | 
| 1.0.0 | 轮播图插件 | 李成龙 |

# API

| 属性&方法 | 类型 | 简介 | 
| :--: | :--: | :--: | 
| [el](#api-el) | 属性 | 最外层容器 |
| [imgBox](#api-imgBox) | 属性 | 图片容器 |
| [times](#api-times) | 属性 | 默认轮播时间2s |
| [slidebtn](#api-slidebtn) | 属性 | 图文点击按钮 |
| [active](#api-active) | 方法 | 图文按钮选中状态 |
| [prevBtn](#api-prevBtn) | 方法 | 上一张 |
| [nextBtn](#api-nextBtn) | 方法 | 下一张 |
| [play](#api-play) | 方法 | 轮播函数 |
| [move](#api-move) | 方法 | 轮播方法 |
| [index](#api-index) | 方法 | 当前图片序号 |
| [next](#api-next) | 方法 | 下一张图片序号 |

