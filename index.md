---
redirect_to: "https://geometryexpressions.pages.dev/"
---

# 几何表达式安装指南

## 相关链接

> 能找到这个站，说明你肯定很了解这个软件，所以不写介绍了 ~~懒~~

- 官网 <https://geometryexpressions.com/>

- feature <https://geometryexpressions.com/gx/features.html>

- 在线体验 <https://geometryexpressions.com/gxweb/>

- 和 Mathematica 的联动 <https://www.wolfram.com/products/applications/geometryexpressions/>

## 软件下载

- 软件安装包都在仓库里，3.3.11 的中文包翻译有点不好，替换的语言包也在仓库里
- 3.4 版本暂时无人解决，安装包在 release 里面，md5sum `c7c2e9a85b98559a55810403fd232395  GEv3_4_SP1_setup.exe`

## 如何更换成 TeX 的字体

1. 下载 [Latin Modern Math](http://www.gust.org.pl/projects/e-foundry/lm-math/download/latinmodern-math-1959.zip) 字体并安装
2. 编辑 - 参数配置

   伪代码

   ```py
   for 属性 in 参数配置:
       属性.字体 = Latin Modern Math
       if 格式不对:
           属性.字体 = Euclid
   ```

---

> QQ 群 822606694

有问题欢迎 PR , issue
