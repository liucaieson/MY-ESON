## My notes

## <div id="react">REACT</div>- [<div id="react">REACT</div>](#div-idreactreactdiv)
  - [1.pure Components和Components的区别？PureComponent 将对属性和状态进行浅比较](#1pure-components和components的区别purecomponent-将对属性和状态进行浅比较)
  - [2.React的props和state分别是什么？](#2react的props和state分别是什么)
  - [3.React 中 setState 什么时候是同步的，什么时候是异步的](#3react-中-setstate-什么时候是同步的什么时候是异步的)
  - [4.什么情况下需要使用 shouldComponentUpdate](#4什么情况下需要使用-shouldcomponentupdate)
  - [5.React如何插入富文本](#5react如何插入富文本)
  - [6.什么情境下使用传送门portals](#6什么情境下使用传送门portals)
  - [7.HTML 和 React 事件处理有什么区别?](#7html-和-react-事件处理有什么区别)
  - [8.什么是 "key" 属性，在元素数组中使用它们有什么好处?为什么不能使用index来做key](#8什么是-key-属性在元素数组中使用它们有什么好处为什么不能使用index来做key)
  - [9.是否使用过错误边界，如果发生错误如何避免组件数崩溃](#9是否使用过错误边界如果发生错误如何避免组件数崩溃)
  - [10.什么是受控组件和非受控组件。](#10什么是受控组件和非受控组件)
  - [11.React的生命周期，那些被废弃，新版本增加了那个声明周期。](#11react的生命周期那些被废弃新版本增加了那个声明周期)
  - [12.什么是高阶组件](#12什么是高阶组件)
  - [13.children 属性是什么?](#13children-属性是什么)
  - [14.每次组件渲染时调用函数的常见错误是什么？](#14每次组件渲染时调用函数的常见错误是什么)
  - [15.为什么有组件名称要首字母大写?](#15为什么有组件名称要首字母大写)
  - [16.你在react项目如何使用样式](#16你在react项目如何使用样式)
  - [17.如果在构造函数中使用 setState() 会发生什么？](#17如果在构造函数中使用setstate会发生什么)
  - [18.在组件类中方法的推荐的书写顺序是什么?](#18在组件类中方法的推荐的书写顺序是什么)
  - [19.如何在调整浏览器大小时重新渲染视图?](#19如何在调整浏览器大小时重新渲染视图)
  - [20.你怎么做的权限验证？](#20你怎么做的权限验证)
- [<div id="redux"> Redux</div>](#div-idredux-reduxdiv)
  - [说一下redux。以及redux-thunk和redux-saga，dva.js。](#说一下redux以及redux-thunk和redux-sagadvajs)
  - [聊聊 Redux 和 Vuex 的设计思想](#聊聊-redux-和-vuex-的设计思想)
  - [我可以在redux触发一个action吗？](#我可以在redux触发一个action吗)
  - [访问 Redux Store 的正确方法是什么?](#访问-redux-store-的正确方法是什么)
  - [国际化（react-intl）](#国际化react-intl)
  - [为什么在componentDidmount里写请求](#为什么在componentdidmount里写请求)
  - [react事件绑定](#react事件绑定)
- [<div id="hooks">Hooks<?div>](#div-idhookshooksdiv)
  - [为什么不能在条件语句循环语句中使用hooks](#为什么不能在条件语句循环语句中使用hooks)
  - [UseCallback 和useMemo](#usecallback-和usememo)
  - [React 项目中有哪些细节可以优化？实际开发中都做过哪些性能优化](#react-项目中有哪些细节可以优化实际开发中都做过哪些性能优化)
- [<div id="browser">浏览器</div>](#div-idbrowser浏览器div)
  - [cookies、session、sessionStorage、localStorage（session储存于服务端，cookies存储于浏览器。本地存储有什么坑](#cookiessessionsessionstoragelocalstoragesession储存于服务端cookies存储于浏览器本地存储有什么坑)
  - [多window tab页签之间的通信怎么做](#多window-tab页签之间的通信怎么做)
  - [Xss攻击，反射性，储存型，dom型；](#xss攻击反射性储存型dom型)
- [<div id="css">CSS</div>](#div-idcsscssdiv)
  - [是否熟悉flex。](#是否熟悉flex)
  - [css实现固定宽高比用](#css实现固定宽高比用)
  - [Css绘制三角形](#css绘制三角形)
  - [实现多列等高布局](#实现多列等高布局)
  - [背景定位不随元素滚动的时候，背景定位是相对于父级还是视口？](#背景定位不随元素滚动的时候背景定位是相对于父级还是视口)
  - [用过object-fit吗？](#用过object-fit吗)
  - [设置按钮禁用的时候在css方面有什么注意的吗？](#设置按钮禁用的时候在css方面有什么注意的吗)
  - [如何是block元素想inline-block一样收缩宽度包裹元素？](#如何是block元素想inline-block一样收缩宽度包裹元素)
  - [了解过grid布局吗?](#了解过grid布局吗)
  - [Word-break，word-wrap，white-space区别？](#word-breakword-wrapwhite-space区别)
  - [什么情况会导致网页重绘，和重排，](#什么情况会导致网页重绘和重排)
  - [Css会阻塞渲染吗？](#css会阻塞渲染吗)
  - [DOMContentLoaded方法会在什么时候执行？](#domcontentloaded方法会在什么时候执行)
  - [Background书写顺序](#background书写顺序)
- [<div id="js">JS</div>](#div-idjsjsdiv)
  - [For in 迭代和for of区别](#for-in-迭代和for-of区别)
  - [websocket有时会出现掉线的问题，怎么解决？](#websocket有时会出现掉线的问题怎么解决)
  - [如何判断图片加载完成。](#如何判断图片加载完成)
  - [10个ajax请求，全部返回结果，只允许3次失败。失败3次报错。](#10个ajax请求全部返回结果只允许3次失败失败3次报错)
  - [基于localStorage设计一个1m的缓存系统](#基于localstorage设计一个1m的缓存系统)
  - [Fetch](#fetch)
  - [手机软键盘只允许用户输入数字和小数点](#手机软键盘只允许用户输入数字和小数点)
  - [深拷贝和浅拷贝的区别？](#深拷贝和浅拷贝的区别)
  - [js函数参数通过的值传递还是引用传递](#js函数参数通过的值传递还是引用传递)
  - [如何给fetch增加超时时间](#如何给fetch增加超时时间)
  - [1.如何前端进行代码检测](#1如何前端进行代码检测)
  - [2.你的前端项目资源缓存配置策略](#2你的前端项目资源缓存配置策略)
  - [web font](#web-font)
  - [什么是 Open Graph 协议，用来做什么](#什么是-open-graph-协议用来做什么)
  - [SVG图标颜色文字继承与填充](#svg图标颜色文字继承与填充)
- [<div id="vue">VUE</div>](#div-idvuevuediv)
  - [Vue动画的原理](#vue动画的原理)
  - [vue中provide和inject 用法](#vue中provide和inject-用法)
  - [Vue中mixins的用法](#vue中mixins的用法)
  - [Vue的$on 和 $emit](#vue的on-和-emit)
  - [那你能讲一讲MVVM吗？](#那你能讲一讲mvvm吗)
  - [简单说一下Vue2.x响应式数据原理](#简单说一下vue2x响应式数据原理)
  - [那你知道Vue3.x响应式数据原理吗？](#那你知道vue3x响应式数据原理吗)
  - [再说一下vue2.x中如何监测数组变化](#再说一下vue2x中如何监测数组变化)
  - [nextTick知道吗，实现原理是什么？](#nexttick知道吗实现原理是什么)
  - [说一下Vue的生命周期](#说一下vue的生命周期)
  - [再说一下Computed和Watch](#再说一下computed和watch)
  - [说一下v-if和v-show的区别](#说一下v-if和v-show的区别)
  - [组件中的data为什么是一个函数？](#组件中的data为什么是一个函数)
  - [说一下v-model的原理](#说一下v-model的原理)
  - [Vue事件绑定原理说一下](#vue事件绑定原理说一下)
  - [Vue模版编译原理知道吗，能简单说一下吗？](#vue模版编译原理知道吗能简单说一下吗)
  - [Vue2.x和Vue3.x渲染器的diff算法分别说一下](#vue2x和vue3x渲染器的diff算法分别说一下)
  - [再说一下虚拟Dom以及key属性的作用](#再说一下虚拟dom以及key属性的作用)
  - [keep-alive了解吗](#keep-alive了解吗)
  - [Vue中组件生命周期调用顺序说一下](#vue中组件生命周期调用顺序说一下)
  - [Vue2.x组件通信有哪些方式？](#vue2x组件通信有哪些方式)
  - [你都做过哪些Vue的性能优化？](#你都做过哪些vue的性能优化)
- [<div id="webpack">webpack</div>](#div-idwebpackwebpackdiv)
  - [Webpack loader和 plugin的区别](#webpack-loader和-plugin的区别)
  - [Webpack tree-shaking](#webpack-tree-shaking)
  - [webpack的打包原理](#webpack的打包原理)
  - [为什么要使用pm2](#为什么要使用pm2)
  - [什么是服务端渲染](#什么是服务端渲染)
  - [ts 的as const 什么意思](#ts-的as-const-什么意思)

### 1.pure Components和Components的区别？PureComponent 将对属性和状态进行浅比较
React fober架构说说你的；理解（在 react16 之前的版本中，组建的渲染是同步的动作，如果组件包含很多层子组件，渲染时间比较长，在组件渲染的过程中又无法被打断，会导致这期间用户无法与网页进行交互。 所有的任务都是按照先后顺序，没有优先级可言，这样就会导致优先级比较高的任务无法优先被执行。大量的同步计算任务阻塞了浏览器的ui渲染。 解决思路：讲任务切割定时把控制权交给浏览器
### 2.React的props和state分别是什么？
setState()会对一个组件的 state 对象安排一次更新。当 state 改变了，该组件就会重新渲染。props（“properties” 的缩写）和 state 都是普通的 JavaScript 对象。它们都是用来保存信息的，这些信息可以控制组件的渲染输出，而它们的几个重要的不同点就是：
props 是传递给组件的（类似于函数的形参），而 state 是在组件内被组件自己管理的（类似于在一个函数内声明的变量）。
props 是不可修改的，所有 React 组件都必须像纯函数一样保护它们的 props 不被更改。 由于 props 是传入的，并且它们不能更改，因此我们可以将任何仅使用 props 的 React 组件视为 pureComponent，也就是说，在相同的输入下，它将始终呈现相同的输出。

### 3.React 中 setState 什么时候是同步的，什么时候是异步的
（比如通过onClick引发的事件处理），由React控制的事件处理程序，以及生命周期函数调用setState不会同步更新state 。React控制之外的事件中调用setState是同步更新的。比如原生js绑定的事件，setTimeout/setInterval等因为事件处理函数会修改同步的变量，把更新state放到队列之中，异步更新，同步执行）
### 4.什么情况下需要使用 shouldComponentUpdate
 父组件发生率更新子组件都会更新，用来阻止无用更新
### 5.React如何插入富文本
dangerousLySetInnerHtml
### 6.什么情境下使用传送门portals
（父组件overflowhidden，但子组件想展示，父组件z-index太小，fixed需要放到body第一层，第一个参数dom，react节点，第二个参数挂载节点）
### 7.HTML 和 React 事件处理有什么区别?
（html小写，可以用false阻止，react驼峰，e.PerventDefault阻止）
### 8.什么是 "key" 属性，在元素数组中使用它们有什么好处?为什么不能使用index来做key
（key来帮助react标识那些项有更改）
### 9.是否使用过错误边界，如果发生错误如何避免组件数崩溃
（componentDidCatch）
### 10.什么是受控组件和非受控组件。
### 11.React的生命周期，那些被废弃，新版本增加了那个声明周期。
挂载`constructor(),`
 说说这个钩子的用法`getDerivedStateFromProps(),` 静态函数,不能使用this,props变化会触发,根据props和state,来更新state.
`render()`, 
`componentDidMount()` 
更新`getDerivedStateFromProps()`, 
`shouldComponentUpdate()`,性能优化
` render()`, 
`getSnapshotBeforeUpdate()` 首次渲染不会更新
和 `componentDidUpdate()`
卸载 `componentWillUnmount`

### 12.什么是高阶组件
（高阶组件(HOC) 就是一个函数，且该函数接受一个组件作为参数，并返回一个新的组件）
### 13.children 属性是什么?
（允许你将组件作为数据传递给其他组件，就像你使用的任何其他组件一样）React.Children.map、React.Children.forEach。和map方法的区别
### 14.每次组件渲染时调用函数的常见错误是什么？
你需要确保在将函数作为参数传递时未调用该函数。传递函数本身应该没有括号：(在组件上写函数，带不带括号，什么时候不带)
### 15.为什么有组件名称要首字母大写?
### 16.你在react项目如何使用样式
Cssmoudle 使用css classname库来组装 , css in js的方式
### 17.如果在构造函数中使用 setState() 会发生什么？
(除了设置状态对象之外，React 还会重新渲染组件及其所有的子组件，构造函数直接设置state， this.State == ‘xx’)
### 18.在组件类中方法的推荐的书写顺序是什么?
### 19.如何在调整浏览器大小时重新渲染视图?
（监听和移除监听）
### 20.你怎么做的权限验证？

## <div id="redux"> Redux</div>
### 说一下redux。以及redux-thunk和redux-saga，dva.js。
(处理异步操作，redux操作是同步的，没有副作用。因为视图的渲染是同步的网络请求是异步的，请求结束后，视图可能渲染完毕，数据也就没用的，redux就是解决这个问题，异步解决视图更新。)
单一数据源，state只读，reducer必须是纯函数，
Redux-Thunk：提供Redux的异步解决方案，弥补Redux功能的不足，让dispatch多支持了函数类型，转换异步操作，生成原始的action，这样，reducer函数就能处理相应的action
store为保存的事件
Store对象包含所有数据。如果想得到某个时点的数据，就要对 Store 生成快照。这种时点的数据集合，就叫做 State。
State 的变化，会导致 View 的变化。但是，用户接触不到 State，只能接触到 View。所以，State 的变化必须是 View 导致的。Action 就是 View 发出的通知，表示 State 应该要发生变化了。
Store 收到 Action 以后，必须给出一个新的 State，这样 View 才会发生变化。这种 State 的计算过程就叫做 Reducer。
### 聊聊 Redux 和 Vuex 的设计思想
共同点：都是为响应式编程提供的一个的可预测的状态容器。方便在复杂的应用中进行兄弟组件或者子组件里修改状态。
不同点：状态改变时 redux 通过纯函数（reduce）生成新的 state, 而vux是直接修改状态属性,最后出发相应的跟新操作

### 我可以在redux触发一个action吗？
（不行，反模式）
### 访问 Redux Store 的正确方法是什么?
（在组件中访问 Store 的最佳方法是使用connect()函数，该函数创建一个包裹现有组件的新组件。此模式称为高阶组件，通常是在 React 中扩展组件功能的首选方式。这允许您将状态和 Action 创建者映射到组件，并在 Store 更新时自动传递它们。）
你对设计模式的了解。在哪里需要用到设计模式。）
### 国际化（react-intl）
### 为什么在componentDidmount里写请求
（这里setState会触发重新渲染，constructor，组件未渲染。）
### react事件绑定
React 内部将事件做了兼容处理，原生事件为空函数，将事件代理到了document上。
React 发现事件有对应事件才会绑定React并不是将click事件绑在该div的真实DOM上，而是在document处监听所有支持的事件，当事件发生并冒泡至document处时，React将事件内容封装并交由真正的处理函数运行。这样的方式不仅减少了内存消耗，还能在组件挂载销毁时统一订阅和移除事件。
另外冒泡到 document 上的事件也不是原生浏览器事件，而是 React 自己实现的合成事件。因此我们如果不想要事件冒泡的话，调用 event.stopPropagation 是无效的，而应该调用 event.preventDefault。

##  <div id="hooks">Hooks<?div>
### 为什么不能在条件语句循环语句中使用hooks
1.不要 在 循环、条件语句或者嵌套函数中调用hooks 
2.只能在 React 函数组件中调用hooks
Hooks以链表的形式储存了hooks，在条件语句如果第一次生成了hooks，第二次渲染条件为false会导致取到了上一个hooks。

### UseCallback 和useMemo 
`useCallback` 和 `useMemo `都是性能优化的手段，在声明周期内缓存函数，避免多次渲染。
`useCallback`需要配合`React.memo`使用
`React.memo`对比函数组件的props

### React 项目中有哪些细节可以优化？实际开发中都做过哪些性能优化
资源减少式最有效的提升首屏加载的体验
减少子组件渲染

##  <div id="browser">浏览器</div>
### cookies、session、sessionStorage、localStorage（session储存于服务端，cookies存储于浏览器。本地存储有什么坑
（cookies 只有4kb，可以被浏览器带上。Local。Ios隐私模式，会报错）
Localsorage的异常处理用try catch处理
但在实际过程中甚至可能出现无法setItem()这样的低级bug。因此我建议，可以通过在try/catch结构里set/get一个测试数据有无出现异常来判断该浏览器是否支持localstorage，当然测试完后记得删掉测试数据哦。
Localstorage 在某些浏览器会有bug，比如，在iPhone/iPad上有时设置setItem()时会出现诡异的QUOTA_EXCEEDED_ERR错误，这时一般在setItem之前，先removeItem()就ok了。

### 多window tab页签之间的通信怎么做
（
·  window.open与window.opener （基于当前window生成子window，实现父->子window的通信）
·  localStorage与window.onstorage （监听onstorage的event对象key的变化，实现tab间通信）
·  BroadCast Channel （创建一个单独通信通道，tab在这个通道内进行通信）
·  Shared worker （开启一个共享的工作线程，tab在这个共享线程内进行通信）
例如：点击图片打开一个新的window，1s后替换成别的图片。（opener是父窗口的实例。）
）

### Xss攻击，反射性，储存型，dom型；
反射型：提交的不可信的数据被立刻返回（比如浏览器后面加恶意参数）。（主要是攻击者设计链接采用社会工程学手段猜用户行为）
储存型：和反射型类似，储存型sxx会持久保存于应用的储存中，常常利用后端数据库保存恶意代码，有时候会用日志文件。
DOM XSS：比如eval（）会执行恶意代码。
绕过xss防御机制：（有的利用广告动态插入脚本，利用社会工程，骗术，发邮件钓鱼攻击，网站钓鱼，）
钓鱼攻击
中间人攻击：
无线攻击：

## <div id="css">CSS</div>
### 是否熟悉flex。
（flex-grow：项目的放大比例，默认为0，即如果存在剩余空间，也不放大。flex-shrink：项目的缩小比例，默认为1，即如果空间不足，该项目将缩小。）
实现函数柯里化（）

### css实现固定宽高比用
（padding-top的百分比是相对于包含块的宽度而不是高度）
Margin负边距的差异（左边距为负是左移，右边距为负是左拉，上下同理）
Flex布局，当flex-grow小于1时，什么表现（按照比例分配剩余空间，不分配全部）

### Css绘制三角形
（border：100px solid，宽度和高度设置0，再设置边框颜色。）
### 实现多列等高布局
（父：display:table;子：display：table-cell）
### 背景定位不随元素滚动的时候，背景定位是相对于父级还是视口？
（视口，background-attactmant:fixed）
### 用过object-fit吗？
（图片指定尺寸后可以指定contain或者cover保持比例）
### 设置按钮禁用的时候在css方面有什么注意的吗？
（颜色，鼠标状态cursor：not-allowed）
### 如何是block元素想inline-block一样收缩宽度包裹元素？
（with：Fit-content）
### 了解过grid布局吗?
(grid布局是flex布局的补充)
### Word-break，word-wrap，white-space区别？
white-space控制空白字符，控制自动换行，
word-break控制单词如何被拆分换行碰到边界一律换行
word-wrap控制单词拆分换行只有长到溢出的单词会被拆分换行）          
### 什么情况会导致网页重绘，和重排，
（重绘：修改dom，修改样式表，用户事件。如何减少重绘和重排，合并dom操作和样式修改。批量修改dom，隐藏元素修改后再显示，使用文档片段doument.Fragment构建一个子树，再拷贝回文档，讲元素拷贝到一个脱离稳定的节点，在拷贝回来、动画使用定位脱离文档，css3加速）
### Css会阻塞渲染吗？
css不会阻塞dom解析，css会阻塞dom渲染，css加载会阻塞后面的js语句执行
### DOMContentLoaded方法会在什么时候执行？
（js在css前面，不会等待css加载完毕就会触发这个事件，js在css的后面会在css加载完毕执行。）
### Background书写顺序
（color ，image repeat attachment  postion）

## <div id="js">JS</div>

### For in 迭代和for of区别
1.index索引为字符串型数字，不能直接进行几何运算
2.遍历顺序有可能不是按照实际数组的内部顺序
3.使用for in会遍历数组所有的可枚举属性，包括原型。所以for in更适合遍历对象，不要使用for in遍历数组。for of不能遍历对象
for in更适合遍历对象，不要使用for in遍历数组，for of遍历的只是数组内的元素

### websocket有时会出现掉线的问题，怎么解决？
（心跳机制,x短线时间过长则轮询）
### 如何判断图片加载完成。
有一个方法image.onload
### 10个ajax请求，全部返回结果，只允许3次失败。失败3次报错。
```
let errorCount = 0 
let p = new Promise((resolve, reject) => { if (success) { resolve(res.data) } else { errorCount++ if (errorCount > 3) {
 // 失败次数大于3次就应该报错了 reject(error) } else { resolve(error) } } }) Promise.all([p]).then(v => { console.log(v); });
```

### 基于localStorage设计一个1m的缓存系统
（每个对象，需要添加两个属性过期时间和储存时间。利用一个属性保存系统中目前所占空间大小，每次存储都增加该属性。当该属性值大于 1M 时，需要按照时间排序系统中的数据，删除一定量的数据保证能够存储下目前需要存储的数据。每次取数据时，需要判断该缓存数据是否过期，如果过期就删除。
如何做移动端的适配，移动端1px边框的实现。

### Fetch
Fetch为原生方法，fetch第一个参数为url，第二个参数默认为get，使用js的promise对象，执行成功的第一步，可以使用response.json方法取出来，fetch跨域不会带cookie，需要手动指定。服务器返回400 500错误的时候不会reject，只有网络错误导致请求不能完成的时候，才会被reject。
.fetch的响应类型response.,type
(basic同域，cors 服务端设置跨域头，opaque不透明，跨域) 让fetch带上cookie（credentials）；
### 手机软键盘只允许用户输入数字和小数点
（1.模拟键盘，2.正则替换异常字符，3.操作后确认。）
### 深拷贝和浅拷贝的区别？
（深拷贝和浅拷贝是针对复杂数据类型来说的，浅拷贝只拷贝一层，而深拷贝是层层拷贝，这种深copy的缺陷JSON.parse(JSON.stringify(obj))）

### js函数参数通过的值传递还是引用传递
（值传递，对象传递的也是引用地址的值，传递的是副本）




### 如何给fetch增加超时时间
（用promise模拟）


### 1.如何前端进行代码检测
（圈复杂度(Cyclomatic complexity)描写了代码的复杂度，可以理解为覆盖代码所有场景所需要的最少测试用例数量。CC 越高，代码则越不好维护）
### 2.你的前端项目资源缓存配置策略
（ 2个指标，静态资源的加载速度，页面渲染速度，
1.html是不能缓存的，设置极短的max-age的值，或者设置cache-control：no-cache
2。js css img文件
通过版本控制，wenpack打包生成hash值，每次打包才会改变。可以给http header设置较大的缓存时间 ，避免304请求和服务器进行进球链接 
### web font 
浏览器在DOMNode的CSS选择器中发现@font-face时才会下载web fonts文件，这个时候浏览器已经下载完成html/css/js文件；
如果在浏览器发现需要加载font文件之前就告诉浏览器下载font文件，会加快文件下载和页面加载速度。
静态资源加http headers缓存。页面关键文件，路由文件可以做预加载，就是在首屏加载完毕的时候预先加载路由文件。

### 什么是 Open Graph 协议，用来做什么
是一套开放的网页标注协议，通过 meta 标签标注网页的类型

### SVG图标颜色文字继承与填充
svg { fill: #369; }

## <div id="vue">VUE</div>
### Vue动画的原理
（Vue内部通过window.getComputedStyle()这个API接口获取到了transition或animation的结束时间,然后通过绑定transitionend或animationend事件(对应不同的动画结束事件)执行一个回调函数，该回调函数会将DOM节点设置为一个注释节点）

### vue中provide和inject 用法
provide 和 inject 主要为高阶插件/组件库提供用例。这对选项需要一起使用，以允许一个祖先组件向其所有子孙后代注入一个依赖，不论组件层次有多深，并在起上下游关系成立的时间里始终生效。
使用场景：由于vue有$parent属性可以让子组件访问父组件。但孙组件想要访问祖先组件就比较困难。通过provide/inject可以轻松实现跨级访问祖先组件的数据

### Vue中mixins的用法
1、方法和参数在各组件中不共享
如混入对象中有一个 cont:1的变量,在组件A中改变cont值为5，这时候在组件B中获取这个值，拿到的还是1，还是混入对象里的初始值，数据不共享
2、值为对象的选项
如methods,components等，选项会被合并，键冲突的组件会覆盖混入对象的，比如混入对象里有个方法A，组件里也有方法A，这时候在组件里调用的话，执行的是组件里的A方法
3、值为函数的选项
如created,mounted等，就会被合并调用，混合对象里的钩子函数在组件里的钩子函数之前调用，同一个钩子函数里，会先执行混入对象的东西，再执行本组件的
4、与vuex的区别
vuex：用来做状态管理的，里面定义的变量在每个组件中均可以使用和修改，在任一组件中修改此变量的值之后，其他组件中此变量的值也会随之修改。
Mixins：可以定义共用的变量，在每个组件中使用，引入组件中之后，各个变量是相互独立的，值的修改在组件中不会相互影响。
5、与公共组件的区别
组件：在父组件中引入组件，相当于在父组件中给出一片独立的空间供子组件使用，然后根据props来传值，但本质上两者是相对独立的。

### Vue的$on 和 $emit
$on 是用来在监听(注册)自定义事件的。
$emit 是手动触发当前实例上的一个指定事件。


### 那你能讲一讲MVVM吗？
MVVM是Model-View-ViewModel缩写，也就是把MVC中的Controller演变成ViewModel。Model层代表数据模型，View代表UI组件，ViewModel是View和Model层的桥梁，数据会绑定到viewModel层并自动将数据渲染到页面中，视图变化的时候会通知viewModel层更新数据。

### 简单说一下Vue2.x响应式数据原理
Vue在初始化数据时，会使用Object.defineProperty重新定义data中的所有属性，当页面使用对应属性时，首先会进行依赖收集(收集当前组件的watcher)如果属性发生变化会通知相关依赖进行更新操作(发布订阅)。
### 那你知道Vue3.x响应式数据原理吗？
Vue3.x改用Proxy替代Object.defineProperty。因为Proxy可以直接监听对象和数组的变化，并且有多达13种拦截方法。并且作为新标准将受到浏览器厂商重点持续的性能优化。
Proxy只会代理对象的第一层，那么Vue3又是怎样处理这个问题的呢？
（很简单啊）
判断当前Reflect.get的返回值是否为Object，如果是则再通过reactive方法做代理， 这样就实现了深度观测。
监测数组的时候可能触发多次get/set，那么如何防止触发多次呢？
我们可以判断key是否为当前被代理对象target自身属性，也可以判断旧值与新值是否相等，只有满足以上两个条件之一时，才有可能执行trigger。
### 再说一下vue2.x中如何监测数组变化
使用了函数劫持的方式，重写了数组的方法，Vue将data中的数组进行了原型链重写，指向了自己定义的数组原型方法。这样当调用数组api时，可以通知依赖更新。如果数组中包含着引用类型，会对数组中的引用类型再次递归遍历进行监控。这样就实现了监测数组变化。
### nextTick知道吗，实现原理是什么？
在下次 DOM 更新循环结束之后执行延迟回调。nextTick主要使用了宏任务和微任务。根据执行环境分别尝试采用
oPromise
oMutationObserver
osetImmediate
o如果以上都不行则采用setTimeout
定义了一个异步方法，多次调用nextTick会将方法存入队列中，通过这个异步方法清空当前队列。
### 说一下Vue的生命周期
beforeCreate是new Vue()之后触发的第一个钩子，在当前阶段data、methods、computed以及watch上的数据和方法都不能被访问。
created在实例创建完成后发生，当前阶段已经完成了数据观测，也就是可以使用数据，更改数据，在这里更改数据不会触发updated函数。可以做一些初始数据的获取，在当前阶段无法与Dom进行交互，如果非要想，可以通过vm.$nextTick来访问Dom。
beforeMount发生在挂载之前，在这之前template模板已导入渲染函数编译。而当前阶段虚拟Dom已经创建完成，即将开始渲染。在此时也可以对数据进行更改，不会触发updated。
mounted在挂载完成后发生，在当前阶段，真实的Dom挂载完毕，数据完成双向绑定，可以访问到Dom节点，使用$refs属性对Dom进行操作。
beforeUpdate发生在更新之前，也就是响应式数据发生更新，虚拟dom重新渲染之前被触发，你可以在当前阶段进行更改数据，不会造成重渲染。
updated发生在更新完成之后，当前阶段组件Dom已完成更新。要注意的是避免在此期间更改数据，因为这可能会导致无限循环的更新。
beforeDestroy发生在实例销毁之前，在当前阶段实例完全可以被使用，我们可以在这时进行善后收尾工作，比如清除计时器。
destroyed发生在实例销毁之后，这个时候只剩下了dom空壳。组件已被拆解，数据绑定被卸除，监听被移出，子实例也统统被销毁。
### 再说一下Computed和Watch
Computed本质是一个具备缓存的watcher，依赖的属性发生变化就会更新视图。 适用于计算比较消耗性能的计算场景。当表达式过于复杂时，在模板中放入过多逻辑会让模板难以维护，可以将复杂的逻辑放入计算属性中处理。
Watch没有缓存性，更多的是观察的作用，可以监听某些数据执行回调。当我们需要深度监听对象中的属性时，可以打开deep：true选项，这样便会对对象中的每一项进行监听。这样会带来性能问题，优化的话可以使用字符串形式监听，如果没有写到组件中，不要忘记使用unWatch手动注销哦。
### 说一下v-if和v-show的区别
当条件不成立时，v-if不会渲染DOM元素，v-show操作的是样式(display)，切换当前DOM的显示和隐藏。
### 组件中的data为什么是一个函数？
一个组件被复用多次的话，也就会创建多个实例。本质上，这些实例用的都是同一个构造函数。如果data是对象的话，对象属于引用类型，会影响到所有的实例。所以为了保证组件不同的实例之间data不冲突，data必须是一个函数。
### 说一下v-model的原理
v-model本质就是一个语法糖，可以看成是value + input方法的语法糖。 可以通过model属性的prop和event属性来进行自定义。原生的v-model，会根据标签的不同生成不同的事件和属性。
### Vue事件绑定原理说一下
原生事件绑定是通过addEventListener绑定给真实元素的，组件事件绑定是通过Vue自定义的$on实现的。
### Vue模版编译原理知道吗，能简单说一下吗？
简单说，Vue的编译过程就是将template转化为render函数的过程。会经历以下阶段：
o生成AST树
o优化
ocodegen
首先解析模版，生成AST语法树(一种用JavaScript对象的形式来描述整个模板)。 使用大量的正则表达式对模板进行解析，遇到标签、文本的时候都会执行对应的钩子进行相关处理。
Vue的数据是响应式的，但其实模板中并不是所有的数据都是响应式的。有一些数据首次渲染后就不会再变化，对应的DOM也不会变化。那么优化过程就是深度遍历AST树，按照相关条件对树节点进行标记。这些被标记的节点(静态节点)我们就可以跳过对它们的比对，对运行时的模板起到很大的优化作用。
编译的最后一步是将优化后的AST树转换为可执行的代码。
### Vue2.x和Vue3.x渲染器的diff算法分别说一下
简单来说，diff算法有以下过程
同级比较，再比较子节点
先判断一方有子节点一方没有子节点的情况(如果新的children没有子节点，将旧的子节点移除)
比较都有子节点的情况(核心diff)
递归比较子节点
正常Diff两个树的时间复杂度是O(n^3)，但实际情况下我们很少会进行跨层级的移动DOM，所以Vue将Diff进行了优化，从O(n^3) -> O(n)，只有当新旧children都为多个子节点时才需要用核心的Diff算法进行同层级比较。
Vue2的核心Diff算法采用了双端比较的算法，同时从新旧children的两端开始进行比较，借助key值找到可复用的节点，再进行相关操作。相比React的Diff算法，同样情况下可以减少移动节点次数，减少不必要的性能损耗，更加的优雅。
Vue3.x借鉴了 ivi算法和 inferno算法
在创建VNode时就确定其类型，以及在mount/patch的过程中采用位运算来判断一个VNode的类型，在这个基础之上再配合核心的Diff算法，使得性能上较Vue2.x有了提升。(实际的实现可以结合Vue3.x源码看。)
该算法中还运用了动态规划的思想求解最长递归子序列。
### 再说一下虚拟Dom以及key属性的作用
由于在浏览器中操作DOM是很昂贵的。频繁的操作DOM，会产生一定的性能问题。这就是虚拟Dom的产生原因。
Vue2的Virtual DOM借鉴了开源库snabbdom的实现。
Virtual DOM本质就是用一个原生的JS对象去描述一个DOM节点。是对真实DOM的一层抽象。(也就是源码中的VNode类，它定义在src/core/vdom/vnode.js中。)
VirtualDOM映射到真实DOM要经历VNode的create、diff、patch等阶段。
「key的作用是尽可能的复用 DOM 元素。」
新旧 children 中的节点只有顺序是不同的时候，最佳的操作应该是通过移动元素的位置来达到更新的目的。
需要在新旧 children 的节点中保存映射关系，以便能够在旧 children 的节点中找到可复用的节点。key也就是children中节点的唯一标识。

### keep-alive了解吗
keep-alive可以实现组件缓存，当组件切换时不会对当前组件进行卸载。
常用的两个属性include/exclude，允许组件有条件的进行缓存。
两个生命周期activated/deactivated，用来得知当前组件是否处于活跃状态。
keep-alive的中还运用了LRU(Least Recently Used)算法。
### Vue中组件生命周期调用顺序说一下
组件的调用顺序都是先父后子,渲染完成的顺序是先子后父。
组件的销毁操作是先父后子，销毁完成的顺序是先子后父。
加载渲染过程
父beforeCreate->父created->父beforeMount->子beforeCreate->子created->子beforeMount- >子mounted->父mounted
子组件更新过程
父beforeUpdate->子beforeUpdate->子updated->父updated
父组件更新过程
父 beforeUpdate -> 父 updated
销毁过程
父beforeDestroy->子beforeDestroy->子destroyed->父destroyed
### Vue2.x组件通信有哪些方式？
父子组件通信
父->子props，子->父 $on、$emit
获取父子组件实例 $parent、$children
Ref 获取实例的方式调用组件的属性或者方法
Provide、inject 官方不推荐使用，但是写组件库时很常用
兄弟组件通信
Event Bus 实现跨组件通信 Vue.prototype.$bus = new Vue
Vuex
跨级组件通信
Vuex
$attrs、$listeners
Provide、inject
### 你都做过哪些Vue的性能优化？
编码阶段
o尽量减少data中的数据，data中的数据都会增加getter和setter，会收集对应的watcher
ov-if和v-for不能连用
o如果需要使用v-for给每项元素绑定事件时使用事件代理
oSPA 页面采用keep-alive缓存组件
o在更多的情况下，使用v-if替代v-show
okey保证唯一
o使用路由懒加载、异步组件
o防抖、节流
o第三方模块按需导入
o长列表滚动到可视区域动态加载
o图片懒加载
oTree shaking webpack 构建重要的一部分,清除项目中无用代码(webpack 4+自动开启摇树)
oSplit chunks 按需加载
o拆包将项目用到的react的包放到cdn,每次拉取react资源可以强制命中缓存
o经常重构删除多余重复代码
o后端必备gzip


## <div id="webpack">webpack</div>
### Webpack loader和 plugin的区别
Loader主要是文件的转换， plugin不着重操作文件，是流程开始或者结束
plugin是一个扩展器，它丰富了webpack本身，针对是loader结束后，webpack打包的整个过程，它并不直接操作文件，而是基于事件机制工作，会监听webpack打包过程中的某些节点，执行广泛的任务，比如合并压缩

### Webpack tree-shaking
模块必须采用ES6Module语法，才会被处理
消除那些引入了还是没有比使用的方法tree-shaking对函数效果较好 ，因为函数副作用少 .Webpack Tree shaking不会清除IIFE(立即调用函数表达式)

### webpack的打包原理
1.识别入口文件
2.通过逐层识别模块依赖(Commonjs、amd或者es6的import，webpack都会对其进行分析，来获取代码的依赖)
3.webpack做的就是分析代码，转换代码，编译代码，输出代码
4.最终形成打包后的代码
Webapck性能优化
 * 使用高版本的 Webpack （使用webpack4）
 * 多线程/多实例构建：HappyPack(不维护了)、thread-loader
缩小打包作用域：
 * exclude/include (确定 loader 规则范围)
 * resolve.modules 指明第三方模块的绝对路径 (减少不必要的查找)
 * resolve.extensions 尽可能减少后缀尝试的可能性
 * noParse 对完全不需要解析的库进行忽略 (不去解析但仍会打包到 bundle 中，注意被忽略掉的文件里不应该包含 import、require、define 等模块化语句)
 * IgnorePlugin (完全排除模块)
*  合理使用alias
充分利用缓存提升二次构建速度：
 * babel-loader 开启缓存
 * terser-webpack-plugin 开启缓存
 * 使用 cache-loader 或者 hard-source-webpack-plugin
注意：thread-loader 和 cache-loader 兩個要一起使用的話，請先放 cache-loader 接著是 thread-loader 最後才是 heavy-loader
DLL：
 * 使用 DllPlugin 进行分包，使用 DllReferencePlugin(索引链接) 对 manifest.json 引用，让一些基本不会改动的代码先打包成静态资源，避免反复编译浪费时间。


### 为什么要使用pm2
对于这个问题，先说说我的看法，最基本的原因是因为node本身是一个单线程应用，它的特点就是所有方法都是串行一次执行，并且node并没有能力像Java一样独自去创建一个新的线程来实现异步操作，如果在执行I/O中遇到了阻塞就会降低整个应用的执行效率，导致CPU使用率高等不利原因。
因此在这种模式下，一个线程只能处理一个任务，要想提高吞吐量必须通过多线程。虽然单线程的好处有很多比如避免了线程同步或者死锁、状态同步等等之类的问题，但是在应用和计算能力要求日益倍增的今天，单线程最大的弊端就是无法利用多核CPU带来的优势来提升运行效率。
PM2是具有内置负载平衡器的Node.js / io.js应用程序的生产过程管理器。它使您可以使应用程序永远保持活动状态，无需停机即可重新加载它们，并简化常见的系统管理任务

### 什么是服务端渲染
客户端渲染时由客户端的js控制的,服务端时服务端返回的字符串
同构.,服务端完成页面结构,但是事件需要在客户端绑定
服务端store共享数据,应该时每人一份.createSrore应该为函数

### ts 的as const 什么意思
为了解决let赋值问题的，将一个mutable的变量改为readonly。
避免将类型推断为联合类型。
但我们可以通过添加一个 const assertion 来解决redux里面action的类型严格为声明的type而不是字符串








	
	

