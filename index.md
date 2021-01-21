# 几何表达式安装指南

## 相关链接

> 能找到这个站，说明你肯定很了解这个软件，所以不写介绍了 ~~懒~~

- 官网 <https://geometryexpressions.com/>

- feature <https://geometryexpressions.com/gx/features.html>

- 在线体验 <https://geometryexpressions.com/gxweb/>

- 和 Mathematica 的联动 <https://www.wolfram.com/products/applications/geometryexpressions/>

## 软件下载

- 软件安装包都在仓库里，3.3.11 的中文包翻译有点不好，替换的语言包也在仓库里

- 假如无法从仓库下载安装包，这里是 [Sharepoint 下载地址](https://wuyudi-my.sharepoint.com/:f:/g/personal/wuyudi_wuyudi_onmicrosoft_com/ErIWgiOytddNpxqLPxhTYjIBVaHLKF47R7VutKWvhiWFPw?e=O2w9he)

## 备注

> <http://www.sousou88.com/software/2076778.html> 某软件站发现的 3.4
>
> 群友指出是李鬼
>
> > 是骗人的，前天官网申请试用发的链接显示还是 3.3。以前见过别的软件用过类似套路，让人误以为他们有更新版本，好收割流量

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
