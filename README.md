# Revit-glTF

#### 介绍
主要是Revit的二次开发的插件，其中主要是基于Revit2020进行的，实现从Revit中把建筑模型导出来，使用的是GLTF格式和3dtiles的编码。

这个是好用的至少是至今发现上最好用最实用，比如解决了Node、纹理丢失、压缩等问题

支持revit2020~revit2023，项目依赖于revit，通用构件的合并以及C#对draco算法库的封装，拥有极快的导出速度和极高的压缩率。


#### 支持

1、支持revit带材质导出GLTF

2、支持导出revit法向量、UV

3、支持draco多线程压缩

4、支持相同构件合并

5、支持导出gltf/glb

6、支持导出revit属性

7、支持导出3dtiles格式

#### 安装教程
将编译文件直接拷贝到 C:\ProgramData\Autodesk\Revit\Addins\目录下，对应的Revit版本目录

#### 开发教程

用Visual Studio打开sln编译Revit2GLTF模块（依赖RevitAPI、RevitAPIUI、Newtonsoft）。如果你想重新编译修改DracoNet需要重新引入draco的文件头和静态库
