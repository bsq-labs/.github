<div align="center">

# BSQ Labs

**个人前端 / 跨端工具与实验的孵化仓库。**

[English](./README.md)

</div>

---

## 条件编译工具套件

面向前端主流源码类型（xml, css, js），基于 AOT 以特殊注释作为编译指令进行条件编译，以达到对源码内容根据不同目标平台进行精确裁剪，减少打包体积，减轻运行时压力，可用于内存或性能优化，多端复用 / 跨端 / 跨平台方案的编译端方案等。

1. 面向 js 文件：https://www.npmjs.com/package/babel-plugin-conditional-compile-with-comment
2. 面向 css 文件：https://www.npmjs.com/package/postcss-plugin-conditional-compile
3. 面向 xml 类的模版文件：https://www.npmjs.com/package/xml-conditional-compile
