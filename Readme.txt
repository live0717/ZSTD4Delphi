ZSTD 1.4.8库静态链接Delphi移植，
网址：https://github.com/facebook/zstd/releases

ZSTD是Facebook研发的一种优秀压缩算法，在默认压缩率设定下, ZSTD的速度比ZIPLIB的最高速度设置快一倍以上同时压缩率比ZIPLIB的最大压缩率更高

对于带宽和配置都非常有限的廉价云服务器来说，这种技术可以大幅度提升服务器服务能力。

对于LINUX和移动平台来说，DELPHI可以直接链接.A格式的静态链接库，对于WINDOWS来说，最简单靠谱的方法还是调用DLL。

本方案仅面向有静态链接强迫症的码农使用

本方案目标代码用MINGW64 GCC 10.2编译，64位下强制avx2指令集，32位下强制sse2指令集，因此，64位下不支持N系列的ATOM CPU!

作者: 庾伟洪
QQ: 908069876
推荐交流Q群：490269542 (pascal开源项目技术群)