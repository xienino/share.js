##### 使用方法：

```
wxShareData={
    title: name, // 分享标题
    summary: '教育商城上线啦~~赶紧前来学习吧！', // 分享内容
    pic: pic, // 分享图片
    url: targeturl, // 分享链接
    WXconfig: {
        swapTitleInWX: false, // 是否标题内容互换（仅朋友圈，因朋友圈内只显示标题）
        appId: appId, // 公众号的唯一标识
        timestamp: timestamp, // 生成签名的时间戳
        nonceStr: nonceStr, // 生成签名的随机串
        signature: signature // 签名
    }
};
setShareInfo(wxShareData);
```

更多配置参数，详见代码