**开篇词**

**要干嘛**：写一个Rust系列

**啥目的**：带大家学习未来语言<font color="red">Rust</font> :smile:

**系列叫啥名字**：拥抱未来语言Rust

**发文时间**：每周六和每周日:laughing:

**预计章节**：60回

**互动方式**：微信群和公众号(文末有加入方式)

##### 整个系列布局：
- 第一部分：Rust语法快速学习
- 第二部分：Rust设计模式
- 第三部分：Rust数据结构和算法，爽刷Leecode
- 第四部分：Rust精湛小项目，含web开发、量化开发
  

![系列布局](./images/系列布局v2.png)
---

整个系列需要接收读者的反馈和答疑，以便更好的修正文章内容，所以建立微信群增加互动性，你可以在微信群里面提出反馈意见，或者和群友进行心得交流，亦或进行催更呐喊。加入方式是加我微信好友，备注：rust-昵称-其它信息例如：rust-蔓蔓学-大数据，我会将备注为本格式的好友邀请至微信群。

![微信二维码](./images/微信二维码.png)

---

不出意外的话，以后每个周末都会更新一到两篇文章哦，不过文章还是以质量和准确性为主，不会带着问题强行更新的。

再次声明，本系列<font color='red'>完全免费</font>，直到所有章节结束，所以你们的喜爱和传播就是我坚持更新的最大动力，为了不错过更新，可以星标我的公众号防止错过更新:smile:。最后，希望大家喜欢这个系列，可以多多帮忙传播，例如：朋友圈打卡、点个再看，或者你也写博客的话可以在文章中提提我:smile:，在此多谢各位捧场！

本系列文章，我也会在GitHub上进行同步，因为公众号发送之后修改很麻烦，且有一定的修改次数的限制，没办法进行整体的调整。感兴趣的可以点击阅读全文进入GitHub，同时所有的源代码也在GitHub上哦，感兴趣的可以star一下:smile:。
让我们一起期待吧。


### 微信公众号文章传送门
[开篇词](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484162&idx=1&sn=c2b12585654d3231775b13d14fbbcf0f&chksm=cfe11d30f8969426f5f94e74ffe33b273a52daef7ebf65234155a8343d7c82ba127cf68705bf&token=717589962&lang=zh_CN#rd)

[番外篇 我的成长故事](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484168&idx=1&sn=4a5c2cebc7e958d038288dd231f56048&chksm=cfe11d3af896942c9638bb12463c2faa94a57f0c14676bf977483df46ba3aa072a519cee380a&token=717589962&lang=zh_CN#rd)

### 基础篇 

[第一回 环境准备](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484170&idx=1&sn=4e880a4ca55af9dfa489469ba6b02370&chksm=cfe11d38f896942ee5f086ac08949e69604df2a71701bba80c4e2bcb88e3d45b444562f6bbb4&token=717589962&lang=zh_CN#rd)

[第二回 第一性原理看类型系统](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484186&idx=1&sn=201e3b84de4c813844cc87bddf13a2fd&chksm=cfe11d28f896943e6df94027e6ad50acae6646cddb85150783b15baa76c76c1498ca534c6c29&token=717589962&lang=zh_CN#rd)

[第三回 基本约定](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484197&idx=1&sn=3e1ff57800c00bae425a97a77cdec0d6&chksm=cfe11d17f8969401a39414536420aee96a30e18f011b13fd03f2d9fb1266520c08c595129065&token=2086026546&lang=zh_CN#rd)

[第四回 认识变量常量和标量](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484205&idx=1&sn=ec2e875d1b3930cf4d3dc7ba5c00a79f&chksm=cfe11d1ff8969409c39fd79c4d9e2f82033e6f43a55924cab9b474552647816963ea12f8298d&token=2086026546&lang=zh_CN#rd)

[第五回 Rust中的核心数据类型](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484211&idx=1&sn=76a20ae3dc77827a046914e61edd28d7&chksm=cfe11d01f89694172777713897dd36fd5b3a639289e0c816a51d2ebb8a1b792c1c3753252539&token=2086026546&lang=zh_CN#rd)

[第六回 Rust泛型](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484216&idx=1&sn=31465680eb95faa7b4631eaef1e2e504&chksm=cfe11d0af896941c2cf414fcb141ae8ffe7eb24f312731d62934f6b1fa9351939b53b5aec63b&token=2086026546&lang=zh_CN#rd)

[第七回 Rust的灵魂特征](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484225&idx=1&sn=8981c62dd4e2cb9b3d4ec4d65e70b1c9&chksm=cfe11d73f89694652a7566584e4ba878070eb0695f9afde71280c9221883abf110620549e69a&token=2086026546&lang=zh_CN#rd)

[第八回 所有权和引用](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484234&idx=1&sn=bb345b5beb1ed7d683f604b21d5eedcd&chksm=cfe11d78f896946eefc8d5bcd46e07ad831a17b5acea4ba8abd7b6d09981727ee8b8da9cfd84&token=1876812958&lang=zh_CN#rd)

[第九回 生命周期](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484240&idx=1&sn=9974e08e82d2ffa3e4e9006588a6c897&chksm=cfe11d62f8969474a66050ea3683eff82bb06cd18ef4a46a07862cbed485d6a8b4e9420d435e&token=1876812958&lang=zh_CN#rd)

[第十回 切！这就是指针的本质](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484258&idx=1&sn=918ac5af1be97d0e63f55243c215738a&chksm=cfe11d50f8969446d3e6e43a806ebbc75a9b78f6483e8edf01d480a4525882f1a62103f01922&token=1955546580&lang=zh_CN#rd)

[第十一回 切！这就是Rust中的智能指针，看这一篇足够了](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484265&idx=1&sn=558001ea5de5e2679a9eadcf93330eaa&chksm=cfe11d5bf896944d274f0e83856d6308411f78184a3ee438c885f300b9d59aae2cbe489d533a&token=1955546580&lang=zh_CN#rd)

[第十二回 用闭包迭代器进行函数式编程，体验飞一般的感觉](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484271&idx=1&sn=65a4a012d3a2f9e11cee0ff87e55298d&chksm=cfe11d5df896944bc5d011dbbe3c11087590743d7d43c615971a6a9bcf08243973ae0f07a2b1&token=923462531&lang=zh_CN#rd)

[第十三回 集合了集合](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484299&idx=1&sn=f5b2e9d8f04a2dc43c9aaebd3406068e&chksm=cfe11db9f89694afa7f2528c989ada878a4832a1eb3831c8b4f29ba29885b50a8f3eb143088b&token=923462531&lang=zh_CN#rd)

[第十四回 控制的艺术](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484306&idx=1&sn=2de5e4bd500d8dead5e9f2fc8074bb8c&chksm=cfe11da0f89694b63289cd984c050fe076dbf667a95b32ed61a15d8aeda76b8e3b4a5a5e2e64&token=923462531&lang=zh_CN#rd)

[第十五回 异常处理的哲学](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484311&idx=1&sn=fb890717b5bdec96b5c3fb496980f688&chksm=cfe11da5f89694b3a0a3c0284d1d148b1d0e4d0862d53075a5bf13cde3d38881a499b9e1b6c6&token=923462531&lang=zh_CN#rd)

[第十六回 生产级别workspace](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484319&idx=1&sn=d711008c22811cb626190ff87fb68fd0&chksm=cfe11dadf89694bb7cd91fea0043c874d35beccc962ea138492c3d2644a130fa4a3f512a0bf5&token=923462531&lang=zh_CN#rd)

[第十七回 自动化测试](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484326&idx=1&sn=23f66a3e106e99bcef7aa7fdfb7e530d&chksm=cfe11d94f89694823694ac5ebf3e8fff106bfe3362ded8406a320efa3d1187900ef69020c79e&token=923462531&lang=zh_CN#rd)

[第十八回 宏](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484331&idx=1&sn=e286f632e3225df7a7af5ae515e0cfb3&chksm=cfe11d99f896948f8376b3dac13f986c2aa80328acbac03c9d6c2fefb5d121de0f2aa3def449&token=1459180003&lang=zh_CN#rd)

[第十九回 并发和并行](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484340&idx=1&sn=5c626fd5d5bcdd453e6868fedf39bdfc&chksm=cfe11d86f8969490bba8c83c848c1b4ecbde307ab6f80290f86c072277366077bfdc67133b35&token=1459180003&lang=zh_CN#rd)

[第二十回 万字长文，细说线程同步与线程安全，彻底弄懂Mutex锁、条件变量、原子变量](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484358&idx=1&sn=58ddd8c44d0c0dba2aea9fab13afe5de&chksm=cfe11df4f89694e272182f175285470f5c373452591f960a94ec9c08c60633d874780608eca9&token=1459180003&lang=zh_CN#rd)

[第二十一回 unsafe的超能力](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484367&idx=1&sn=0cfdbf35f9e874c0bdb8839df32aed7e&chksm=cfe11dfdf89694eb5c8cfa12fc0618cd7f4f25f1ba7eed8e24f91c49157570a28cf6447ee78c&token=1459180003&lang=zh_CN#rd)

[第二十二回 点操作符的魔力](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484372&idx=1&sn=859203e6aa90e0668737ddf44bad7dc0&chksm=cfe11de6f89694f04bc2ed0b9cde2cbe42940bf4a9c26e39eca642e048abee19964f6c449714&token=1459180003&lang=zh_CN#rd)

[第二十三回 同样是高并发，async异步编程到底比多线程厉害在哪里](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484379&idx=1&sn=b6672f4f996d05a070f38e761f2a4d7e&chksm=cfe11de9f89694ff7c7e5f98e09234a74b7cec10695c218d0a25e1efaa538a6082ba9593adb8&token=1459180003&lang=zh_CN#rd)

[第二十四回 我又找到宝了，快来看，自引用魔鬼和镇魔神器Pin及Unpin](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484388&idx=1&sn=31a054f25663eae47072c76e80f0e876&chksm=cfe11dd6f89694c0a26a49c43f0ada6d59cd5ae9ecb2a25214bfcff72fde4abb366db79c4134&cur_album_id=3357418700156502025&scene=189#wechat_redirect)

[第二十五回 救命，当你还在犹豫，别人已经在运行代码了！基础部分大终结！开发一个好玩的微群聊天项目，完结撒花](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484400&idx=1&sn=4e82b5d218bb719581c80eb908241863&chksm=cfe11dc2f89694d478f05baa4137c6fce37b4677491e0c151f8bf9a649b86c33a6276aea7ed9&cur_album_id=3357418700156502025&scene=189#wechat_redirect)

### 进阶篇

[进阶篇开篇词，浅浅期待一下23种设计模式的Rust版本，咱们不见不散](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484423&idx=1&sn=c37dc1a61f9b20bf0ae254a1ea75df4e&chksm=cfe11a35f89693231ddc9d6c8144ec4d20982428842b1cc09b7ae3484dee7be4b01d2e7887ad&token=1509466189&lang=zh_CN#rd)

[逼自己看完，你的设计模式应用能力就会提高：迭代器模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484445&idx=1&sn=cb3fff3dd0d5d89468ca6965d7331877&chksm=cfe11a2ff896933999228d8931d7fb370af36357769a889411fb46384ddb761d4b8800d7f49f&token=1509466189&lang=zh_CN#rd)

[别找了，Rust设计模式都在这里了，Rust设计模式之单例模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484454&idx=1&sn=24dc1a58ddd8c4a7631f4c83e9d3ebac&chksm=cfe11a14f89693029e110e2e7d3d01f7b40178fcf090b2b18d4c454ca3fd8924b71e033cc836&token=1509466189&lang=zh_CN#rd)

[别找了，Rust设计模式都在这里了，设计模式之工厂模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484462&idx=1&sn=af290dbe1ef90eba68d1aeb7467b39a0&chksm=cfe11a1cf896930a6d30ebe667cce0ea64109321aa786787df8dfda60594411ed5ed69c1c4bb&token=1509466189&lang=zh_CN#rd)

[别找了，Rust设计模式都在这里了，设计模式之观察者模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484469&idx=1&sn=cdf2f08250f68ae9e49a6632f3eb4d70&chksm=cfe11a07f8969311299b30896ba8d29a695d1e23c26bb98c23d8f49dfc96d820888cd3eb617f&token=1404716041&lang=zh_CN#rd)

[别找了，Rust设计模式都在这里了——适配器模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484476&idx=1&sn=05e2d8f50423b84a34eed48f9547c0cc&chksm=cfe11a0ef8969318ec63602f62c704fe4ae6a8c90532499df4826f8b6022afe00d1bda661bd3&token=1404716041&lang=zh_CN#rd)

[别找了，Rust设计模式都在这里了——策略模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484483&idx=1&sn=f0c2d8de8dd22d84bf8fc881cd3d7961&chksm=cfe11a71f8969367c43aaacb1fa847308b5429a25ab37350bf4010095a6c525f6b74724f80c8&token=1404716041&lang=zh_CN#rd)

[别找了，Rust设计模式都在这里了——外观模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484489&idx=1&sn=148d2cb28c0ed013dd6af332e9cf5da2&chksm=cfe11a7bf896936d0c053b50105de0251932aaaa775df74619a56fdfd46a8535582ef87742fd&token=1404716041&lang=zh_CN#rd)

[别找了，Rust设计模式都在这里了——享元模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484495&idx=1&sn=8529e41ae5be39d82792f0a27b57825d&chksm=cfe11a7df896936bb65dabcb1d27d8d1f12295ced6384ded7b486185031a665400347b2fa4bc&token=1404716041&lang=zh_CN#rd)


[别找了，Rust设计模式都在这里了——代理模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484502&idx=1&sn=0bcc7033a2786aa8d6ec7bc950302df3&chksm=cfe11a64f8969372cbbe9c0f9a87ecfc7ac1ef2a3a6d87f9311cb283c9409c1c651484da48ad&token=1404716041&lang=zh_CN#rd)

[别找了，Rust设计模式都在这里了——命令模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484508&idx=1&sn=2440dfb9aa5dbec0a2f68f5a3c212534&chksm=cfe11a6ef896937842da6b5564d0ca5e80c61a4ab4b036a04a4b1660d185618121fa03e4487f&token=1404716041&lang=zh_CN#rd)

[别找了，Rust设计模式都在这里了——原型模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484514&idx=1&sn=5d4cfae291f3bc24fd528918b2c08c51&chksm=cfe11a50f8969346514d6cd81577f6d7659dbea5a27582fe5806795031de77c0df9e501785f7&token=1404716041&lang=zh_CN#rd)

[别找了，Rust设计模式都在这里了——组合模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484521&idx=1&sn=494b8d5c6e5b84c1622e634603c5e7c7&chksm=cfe11a5bf896934d3ed43142e99306fe0519278f8be44eb10c2eec39d359c18f608f1c7c83a1&token=1404716041&lang=zh_CN#rd)

[别找了，Rust设计模式都在这里了——责任链模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484528&idx=1&sn=5b8f9120b4f4a36b0f794b9cdb9b5ab5&chksm=cfe11a42f8969354fec1705c8e87d5abd22023928026e29688f088feb81daf373b849c42c9ed&token=1404716041&lang=zh_CN#rd)

[别找了，Rust设计模式都在这里了——桥接模式](https://mp.weixin.qq.com/s?__biz=Mzg5MDE5NDc4MQ==&mid=2247484556&idx=1&sn=1eb435a3dbbbae547925692f3b65dcb1&chksm=cfe11abef89693a877349c7624250b01d3c694a203af62463a8056876188d6b9cb0adf52fb4d&token=1404716041&lang=zh_CN#rd)

##### 添加公众号
![微信公众号](./images/wechat_service.jpg)