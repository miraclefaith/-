Python音乐百宝箱
生活不只眼前的苟且，还有音乐和远方。那么，能不能利用python实现对歌曲的分析，对歌曲评价的分析，音乐播放以及音乐创作呢？本次程序主要分为四个部分，第一部分为爬虫千千音乐上的歌曲，对歌曲进行词频分析，并做出漂亮的词云；第二部分爬虫网易云音乐的一首歌的评论，将评论的情感进行正负面的分析；第三部分为制作一个简单的音乐播放器；第四部分为Python制作一个歌词解析器。
相关部分代码已传上。
第一部分：对歌词的词频分析，画出词云
第二部分：爬虫网易云音乐上热门歌曲的评论，并对其进行情感分析。
第三部分：制作一个简单的音乐播放器。
第四部分：利用python做一个歌词解析器 
本文实现了对音乐的四种处理，只能说是实现了一个小的音乐百宝箱。毋庸置疑，python语言给人们带来了非常大的便利。Python分析音乐是一个非常广泛的话题，还有许多的功能可以实现，比如说利用python实现对音频指纹提取（即听歌识曲）的功能，或者实现双声道的分离，或者进行用户听歌数据分析与处理等等。当然我最想实现的功能是python利用网易云音乐接口搭建的音乐推荐，根据单曲歌名推荐相关用户喜爱的歌曲。尝试了好久但是还是不能实现。还有想利用python来写歌词，但是由于运行不稳定，没有写入代码。这可能是遗憾吧。在进行相关功能的尝试时，学习到了很多很有用，很有意思的库，认为由于python语言的便利性，一定具有非常多的应用场景。总体来说，这个项目是由于我对音乐的热爱，创新地做的一个百宝箱，里面的很多处理方法（如中文转化为拼音，中文分词，或者是结果弹出的页面设置等等）都是通用的，具有很高的迁移性，这些代码也是自己通过查询，不停试错，争取最简最后的成果。但是由于对这些掌握还是不够深刻，所以可能在一些问题的解决上有些片面，但是我在每部分后都附有改进方法，有待改进吧。当然 ，我还有进一步的设想，如果实现了更多的功能，可以直接组装成一个模块，相信这样的话可以使音乐的处理更加愉快与方便。
参考文章
(1https://www.cnblogs.com/Kobe10/p/5773821.html
(2https://www.runoob.com/python/python-json.html
(3https://blog.csdn.net/efheoihfe/article/details/79249010
(4https://blog.csdn.net/weixin_34294649/article/details/88772413
(5https://mp.weixin.qq.com/s?__biz=MjM5MTQzNzU2NA==&mid=2651671079&idx=1&sn=6e20f22f0c82aa52f22a99adfc2d97f2&chksm=bd4c6db48a3be4a2f238653ac60d4c283fe5a60cb93ee5bc1d4f101e9d413ef7ff15ebfcdaa6&mpshare=1&scene=1&srcid=&key=1c8d0f39d00e87230d974b0abe5d05ba7f0dc8b7bfff05a01356af9f946dd0fe3a7f0bc8a18c2d069418c5a25e8751a37fb1d9bc8cb088c4eb771020a168500f62ed9a283928b5fab52f585ab49716a4&ascene=1&uin=MjM0OTc5NTc1&devicetype=Windows+10&version=62060833&lang=zh_CN&pass_ticket=uCDHFJpF8ZbwFOrHXGBw0In8UKF0B8saAYwomoUxcxA%3D
(6https://blog.csdn.net/tree_hole/article/details/84072051
(7https://github.com/YogaLin/mayday_lyric_analyze
(8https://blog.csdn.net/qq_28891989/article/details/80375331
