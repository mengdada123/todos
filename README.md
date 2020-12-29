# 这是基于react写的todos小案例

里面基本用到了 传值props。合并最新版本

具体逻辑思维可以借鉴百度脑图：http://naotu.baidu.com/file/abdfa824eef93ab212fe7a6d0c34bd48?token=50be17a360ce2b5c

## 需要修改的地方
- 语法问题（eslint问题）： 例如
  - 尽量是用===而不是==
  - 文件单行不要超过120个字符
  - 一般缩进都是两个字符
  - src/page/list/index.jsx:16 可以写成 () => this.handleClick(id)
  - 尽量少用数字作为变量名的一部分
- 逻辑问题
  - src/page/list/index.jsx:68 不用写三套代码，可以将代码做一个合并
  - 页面组件封装过多，封装了过多层，不便于阅读
- 功能部分
  - 双击列表项之后，输入框应当自动focus
  - 页面离开时，需要存下数据，页面刷新数据不会变化

## 好的地方
- 组件层次清晰
- 文件结构清晰
- 变量命名简单易懂（当然有部分我还是看不太懂啥意思）
- 页面炫酷