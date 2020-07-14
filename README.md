# ECSTest

* 这是一个测试Unity ECS模式的demo，demo是10000个cube的噪波运动
* demo使用Unity 2019.2.1f，需要在Package Manager中安装Hybrid Renderer
* 如果使用常规的实现方式，本机测试帧率在25帧
* 使用ECS模式帧率提升至50帧(开启材质的GPU Instancing帧率可提升至90帧，设置Burst Compile帧率可提升至100帧)
* ECS模式对于同屏海量物体的优化效果是很显著的

