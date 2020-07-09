# 安卓设备树Device Tree开发
## 前言
一台安卓设备，要编译出一个ROM，就必须有以下`三件套`：`Device Tree`、`Kernel` 以及 `Vendor`。
而大部分厂商，由于怕失去原系统的用户（失去广告收入），便不开源以上`三件套`。
于是，机型维护者便会自己开发Device Tree。  
这时，你可能要问了：那`Kernel`和`Vendor`呢？其实关注点不在他俩身上。因为即使厂商没有把`Kernel`开源，仍就可以使用`Prebuilt预编译`内核；而`Vendor`呢，则是驱动文件，几乎都是从官方的`ROM`里提取的。所以，`Device Tree`就成为了最重要的部分。

---

笔者呢，截止到写作本文的日期，仍然是一个技术不是很好的小白。但是，我还是觉得需要在这个仓库里分享一下自己开发`Device Tree`中遇到的坑以及其他的内容。

---

下面是我写的这些博客的链接。

## 链接