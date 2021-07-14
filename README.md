- [REACT](#react)
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
  - [21虚拟dom原理](#21虚拟dom原理)
  - [21react项目中，constructor(){ this.target = this.func.bind(this); },JSX里onChange={this.target}的写法，为什么要比非 bind的func = () => {}的写法效率高 请解释其中的原理](#21react项目中constructor-thistarget--thisfuncbindthis-jsx里onchangethistarget的写法为什么要比非-bind的func----的写法效率高-请解释其中的原理)
  - [react 里如何做动态加载](#react-里如何做动态加载)
- [Hooks](#hooks)
  - [为什么不能在条件语句循环语句中使用hooks](#为什么不能在条件语句循环语句中使用hooks)
  - [UseCallback 和 useMemo](#usecallback-和-usememo)
  - [React 项目中有哪些细节可以优化？实际开发中都做过哪些性能优化](#react-项目中有哪些细节可以优化实际开发中都做过哪些性能优化)
  - [useEffect和useLayoutEffect区别](#useeffect和uselayouteffect区别)
- [Redux](#redux)
  - [说一下redux。以及redux-thunk和redux-saga，dva.js。](#说一下redux以及redux-thunk和redux-sagadvajs)
  - [聊聊 Redux 和 Vuex 的设计思想](#聊聊-redux-和-vuex-的设计思想)
  - [我可以在redux触发一个action吗？](#我可以在redux触发一个action吗)
  - [访问 Redux Store 的正确方法是什么?](#访问-redux-store-的正确方法是什么)
  - [国际化（react-intl）](#国际化react-intl)
  - [为什么在componentDidmount里写请求](#为什么在componentdidmount里写请求)
  - [react事件绑定](#react事件绑定)
- [浏览器Dom Bom](#浏览器dom-bom)
  - [浏览器的回流与重绘](#浏览器的回流与重绘)
  - [cookies、session、sessionStorage、localStorage（session储存于服务端，cookies存储于浏览器。本地存储有什么坑](#cookiessessionsessionstoragelocalstoragesession储存于服务端cookies存储于浏览器本地存储有什么坑)
  - [多window tab页签之间的通信怎么做](#多window-tab页签之间的通信怎么做)
  - [Xss攻击，反射性，储存型，dom型；](#xss攻击反射性储存型dom型)
  - [事件冒泡与捕获](#事件冒泡与捕获)
  - [input 中如何监听值的变化](#input-中如何监听值的变化)
- [CSS](#css)
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
- [JS](#js)
  - [原型链](#原型链)
  - [继承](#继承)
  - [call、apply 以及 bind](#callapply-以及-bind)
  - [For in 迭代和for of区别](#for-in-迭代和for-of区别)
  - [websocket有时会出现掉线的问题，怎么解决？](#websocket有时会出现掉线的问题怎么解决)
  - [如何判断图片加载完成。](#如何判断图片加载完成)
  - [10个ajax请求，全部返回结果，只允许3次失败。失败3次报错。](#10个ajax请求全部返回结果只允许3次失败失败3次报错)
  - [基于localStorage设计一个1m的缓存系统](#基于localstorage设计一个1m的缓存系统)
  - [Fetch](#fetch)
  - [手机软键盘只允许用户输入数字和小数点](#手机软键盘只允许用户输入数字和小数点)
  - [深拷贝和浅拷贝的区别？](#深拷贝和浅拷贝的区别)
  - [js函数参数通过的值传递还是引用传递](#js函数参数通过的值传递还是引用传递)
  - [new的执行过程](#new的执行过程)
  - [promise原理](#promise原理)
  - [如何给fetch增加超时时间](#如何给fetch增加超时时间)
  - [innerHTML和outHTML的区别](#innerhtml和outhtml的区别)
  - [innerText和textContent的区别](#innertext和textcontent的区别)
  - [js事件循环](#js事件循环)
  - [node事件循环](#node事件循环)
  - [如何前端进行代码检测](#如何前端进行代码检测)
  - [你的前端项目资源缓存配置策略](#你的前端项目资源缓存配置策略)
  - [web font 网页字体](#web-font-网页字体)
  - [什么是 Open Graph 协议，用来做什么](#什么是-open-graph-协议用来做什么)
  - [SVG图标颜色文字继承与填充](#svg图标颜色文字继承与填充)
- [VUE](#vue)
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
- [webpack](#webpack)
  - [Webpack loader和 plugin的区别](#webpack-loader和-plugin的区别)
  - [Webpack tree-shaking](#webpack-tree-shaking)
  - [webpack的打包原理](#webpack的打包原理)
- [其他](#其他)
  - [为什么要使用pm2](#为什么要使用pm2)
  - [什么是服务端渲染](#什么是服务端渲染)
  - [ts 的as const 什么意思](#ts-的as-const-什么意思)
  - [如何在https里面发送http请求](#如何在https里面发送http请求)
  - [现在有多个spa的项目，有angular的，有vue的和react的，如何将他们合并成一个大统一的spa项目](#现在有多个spa的项目有angular的有vue的和react的如何将他们合并成一个大统一的spa项目)
  - [node 引入一个模块的过程是什么](#node-引入一个模块的过程是什么)


## REACT

### 1.pure Components和Components的区别？PureComponent 将对属性和状态进行浅比较
React fober架构说说你的；理解（在 react16 之前的版本中，组建的渲染是同步的动作，如果组件包含很多层子组件，渲染时间比较长，在组件渲染的过程中又无法被打断，会导致这期间用户无法与网页进行交互。 所有的任务都是按照先后顺序，没有优先级可言，这样就会导致优先级比较高的任务无法优先被执行。大量的同步计算任务阻塞了浏览器的ui渲染。 解决思路：讲任务切割定时把控制权交给浏览器
### 2.React的props和state分别是什么？
setState()会对一个组件的 state 对象安排一次更新。当 state 改变了，该组件就会重新渲染。props（“properties” 的缩写）和 state 都是普通的 JavaScript 对象。它们都是用来保存信息的，这些信息可以控制组件的渲染输出，而它们的几个重要的不同点就是：
props 是传递给组件的（类似于函数的形参），而 state 是在组件内被组件自己管理的（类似于在一个函数内声明的变量）。
props 是不可修改的，所有 React 组件都必须像纯函数一样保护它们的 props 不被更改。 由于 props 是传入的，并且它们不能更改，因此我们可以将任何仅使用 props 的 React 组件视为 pureComponent，也就是说，在相同的输入下，它将始终呈现相同的输出。

### 3.React 中 setState 什么时候是同步的，什么时候是异步的
1. 合成事件与生命周期钩子函数中 setState 是异步的。
2. 原生事件和定时器事件中 setState 是同步的。
setState 更新过程
1. 每次调用 setState 时，会将 setState 传入的 partialState 参数存储当前组件实例的 state 暂存队列中。
2. 判断当前 React 是否处于批量更新状态，如果是，将当前组件加入待更新的组件队列 dirtyComponent 中。
3. 如果未处于批量更新状态，将批量更新状态标识 isBatchingUpdate 设为 true ，用事务调用前一步方法，保证当前组件加入到待更新组件队列中。
4. 调用事务的 warpper 方法，遍历待更新组件依次执行更新。
5. 执行生命周期componentWillReceiveProps。
6. 将组件的state暂存队列中的 state 进合并，获得最终要更新的 state 对象，并将队列置为空。
7. 执行生命周期 componentShouldUpdate ，根据返回值判断是否要继续更新。
8. 执行生命周期 componentWillUpdate 。
9. 执行真正的更新，render。
10. 执行生命周期 componentDidUpdate 。


### 4.什么情况下需要使用 shouldComponentUpdate
 父组件发生率更新子组件都会更新，用来阻止无用更新
### 5.React如何插入富文本
dangerousLySetInnerHtml
### 6.什么情境下使用传送门portals
（父组件overflowhidden，但子组件想展示，父组件z-index太小，fixed需要放到body第一层，第一个参数dom，react节点，第二个参数挂载节点）
### 7.HTML 和 React 事件处理有什么区别?
（html小写，可以用false阻止，react驼峰，e.PerventDefault阻止）
### 8.什么是 "key" 属性，在元素数组中使用它们有什么好处?为什么不能使用index来做key
（key来帮助react标识那些项有更改），如果用index做key，每次删除操作dom会导致重新用index排序，这是做对比的时候，相同的key文本做了改变了，会导致全部渲染
### 9.是否使用过错误边界，如果发生错误如何避免组件数崩溃
（componentDidCatch）
通过ErrorBoundary捕获渲染过程中的异常，
window.addEventListener('error',cb) 捕获资源或者其他错误的异常，
http拦截器捕获请求异常，让整个项目的异常可控。
### 10.什么是受控组件和非受控组件。
受控组件	
1. 没有维持自己的状态	
2.数据由父组件控制	
3. 通过 props 获取当前值，然后通过回调通知更改	
非受控组件
   保持着自己的状态
   数据由 DOM 控制
   Refs 用于获取其当前值
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
你需要确保在将函数作为参数传递时未调用该函数。
传递函数本身应该没有括号：(在组件上写函数，带不带括号，什么时候不带)
立刻调用的带括号，代表立刻执行
### 15.为什么有组件名称要首字母大写?
避免与html原生标签混合，为了babel的识别
### 16.你在react项目如何使用样式
Cssmoudle 使用css classname库来组装 , css in js的方式
### 17.如果在构造函数中使用 setState() 会发生什么？
(除了设置状态对象之外，React 还会重新渲染组件及其所有的子组件，构造函数直接设置state， this.State == ‘xx’)
### 18.在组件类中方法的推荐的书写顺序是什么?
### 19.如何在调整浏览器大小时重新渲染视图?
（监听和移除监听）
### 20.你怎么做的权限验证？

### 21虚拟dom原理
每当底层数据发生改变时，整个 UI 都将在 Virtual DOM 描述中重新渲染。
然后计算之前 DOM 表示与新表示的之间的差异。
完成计算后，将只用实际更改的内容更新 real DOM。
### 21react项目中，constructor(){ this.target = this.func.bind(this); },JSX里onChange={this.target}的写法，为什么要比非 bind的func = () => {}的写法效率高 请解释其中的原理
bind之后锁定了上下文，不用向上查找
箭头函数是实例上的方法，而函数声明是在原型上的方法。

### react 里如何做动态加载
react.lazy 配合suspense

### React 事件绑定原理
React并不是将click事件绑在该div的真实DOM上，而是在document处监听所有支持的事件，当事件发生并冒泡至document处时，React将事件内容封装并交由真正的处理函数运行。这样的方式不仅减少了内存消耗，还能在组件挂载销毁时统一订阅和移除事件。
另外冒泡到 document 上的事件也不是原生浏览器事件，而是 React 自己实现的合成事件（SyntheticEvent）。因此我们如果不想要事件冒泡的话，调用 event.stopPropagation 是无效的，而应该调用 event.preventDefault。
1 事件注册
组件装载 / 更新。
通过lastProps、nextProps判断是否新增、删除事件分别调用事件注册、卸载方法。
调用EventPluginHub的enqueuePutListener进行事件存储
获取document对象。
根据事件名称（如onClick、onCaptureClick）判断是进行冒泡还是捕获。
判断是否存在addEventListener方法，否则使用attachEvent（兼容IE）。
给document注册原生事件回调为dispatchEvent（统一的事件分发机制）。
2 事件储存
EventPluginHub负责管理React合成事件的callback，它将callback存储在listenerBank中，另外还存储了负责合成事件的Plugin。
EventPluginHub的putListener方法是向存储容器中增加一个listener。
获取绑定事件的元素的唯一标识key。
将callback根据事件类型，元素的唯一标识key存储在listenerBank中。
listenerBank的结构是：listenerBank[registrationName][key]。
3.事件触发执行
触发document注册原生事件的回调dispatchEvent
获取到触发这个事件最深一级的元素
这里的事件执行利用了React的批处理机制
代码示例

<div onClick={this.parentClick} ref={ref => this.parent = ref}>
      <div onClick={this.childClick} ref={ref => this.child = ref}>
          test
     </div>
</div>
首先会获取到this.child
遍历这个元素的所有父元素，依次对每一级元素进行处理。
构造合成事件。
将每一级的合成事件存储在eventQueue事件队列中。
遍历eventQueue。
通过isPropagationStopped判断当前事件是否执行了阻止冒泡方法。
如果阻止了冒泡，停止遍历，否则通过executeDispatch执行合成事件。
释放处理完成的事件。

4 合成事件
调用EventPluginHub的extractEvents方法。
循环所有类型的EventPlugin（用来处理不同事件的工具方法）。
在每个EventPlugin中根据不同的事件类型，返回不同的事件池。
在事件池中取出合成事件，如果事件池是空的，那么创建一个新的。
根据元素nodeid(唯一标识key)和事件类型从listenerBink中取出回调函数
返回带有合成事件参数的回调函数


## Hooks
### 为什么不能在条件语句循环语句中使用hooks
1.不要 在 循环、条件语句或者嵌套函数中调用hooks 
2.只能在 React 函数组件中调用hooks 顶部调用
Hooks以链表的形式储存了hooks，在条件语句如果第一次生成了hooks，第二次渲染条件为false会导致取到了上一个hooks。

### UseCallback 和 useMemo 
`useCallback` 和 `useMemo `都是性能优化的手段，在声明周期内缓存函数，避免多次渲染。
`useCallback`需要配合`React.memo`使用
`React.memo`对比函数组件的props

### React 项目中有哪些细节可以优化？实际开发中都做过哪些性能优化
资源减少式最有效的提升首屏加载的体验
减少子组件渲染

### useEffect和useLayoutEffect区别
useEffect和useLayoutEffect作为组件的副作用，本质上是一样的。共用一套结构来存储effect链表。整体流程上都是先在render阶段，生成effect，并将它们拼接成链表，存到fiber.updateQueue上，最终带到commit阶段被处理。他们彼此的区别只是最终的执行时机不同，一个异步一个同步，这使得useEffect不会阻塞渲染，而useLayoutEffect会阻塞渲染。

##  Redux
### 说一下redux。以及redux-thunk和redux-saga，dva.js。
处理异步操作，redux操作是同步的，没有副作用。因为视图的渲染是同步的网络请求是异步的，请求结束后，视图可能渲染完毕，数据也就没用的，redux就是解决这个问题，异步解决视图更新。
单一数据源，state只读，reducer必须是纯函数，
Redux-Thunk：提供Redux的异步解决方案，弥补Redux功能的不足，让dispatch多支持了函数类型，转换异步操作，生成原始的action，这样，reducer函数就能处理相应的action
store为保存的事件
Store对象包含所有数据。如果想得到某个时点的数据，就要对 Store 生成快照。这种时点的数据集合，就叫做 State。
State 的变化，会导致 View 的变化。但是，用户接触不到 State，只能接触到 View。所以，State 的变化必须是 View 导致的。Action 就是 View 发出的通知，表示 State 应该要发生变化了。
Store 收到 Action 以后，必须给出一个新的 State，这样 View 才会发生变化。这种 State 的计算过程就叫做 Reducer。
### 聊聊 Redux 和 Vuex 的设计思想
共同点：都是为响应式编程提供的一个的可预测的状态容器。方便在复杂的应用中进行兄弟组件或者子组件里修改状态。
不同点：状态改变时 redux 通过纯函数（reduce）生成新的 state, 而vux是直接修改状态属性,最后出发相应的跟新操作

### redux-saga 和 mobx 的比较
1）状态管理

redux-sage 是 redux 的一个异步处理的中间件。
mobx 是数据管理库，和 redux 一样。
2）设计思想

redux-sage 属于 flux 体系， 函数式编程思想。
mobx 不属于 flux 体系，面向对象编程和响应式编程。
3）主要特点

redux-sage 因为是中间件，更关注异步处理的，通过 Generator 函数来将异步变为同步，使代码可读性高，结构清晰。action 也不是 action creator 而是 pure action，
在 Generator 函数中通过 call 或者 put 方法直接声明式调用，并自带一些方法，如 takeEvery，takeLast，race等，控制多个异步操作，让多个异步更简单。
mobx 是更简单更方便更灵活的处理数据。 Store 是包含了 state 和 action。state 包装成一个可被观察的对象， action 可以直接修改 state，之后通过 Computed values 将依赖 state 的计算属性更新 ，之后触发 Reactions 响应依赖 state 的变更，输出相应的副作用 ，但不生成新的 state。
4）数据可变性

redux-sage 强调 state 不可变，不能直接操作 state，通过 action 和 reducer 在原来的 state 的基础上返回一个新的 state 达到改变 state 的目的。
mobx 直接在方法中更改 state，同时所有使用的 state 都发生变化，不生成新的 state。
5）写法难易度

redux-sage 比 redux 在 action 和 reducer 上要简单一些。需要用 dispatch 触发 state 的改变，需要 mapStateToProps 订阅 state。
mobx 在非严格模式下不用 action 和 reducer，在严格模式下需要在 action 中修改 state，并且自动触发相关依赖的更新。
6）使用场景

redux-sage 很好的解决了 redux 关于异步处理时的复杂度和代码冗余的问题，数据流向比较好追踪。但是 redux 的学习成本比 较高，代码比较冗余，不是特别需要状态管理，最好用别
的方式代替。
mobx 学习成本低，能快速上手，代码比较简洁。但是可能因为代码编写的原因和数据更新时相对黑盒，导致数据流向不利于追踪。


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


## 浏览器Dom Bom
### 浏览器的回流与重绘
 * 渲染树中部分或全部元素的尺寸、结构、或某些属性发生改变时，浏览器重新渲染部分或全部文档的过程称为回流
- 页面首次渲染
- 浏览器窗口大小发生改变
- 元素尺寸或位置发生改变
- 元素内容变化（文字数量或图片大小等等）
- 元素字体大小变化
- 添加或者删除可见的DOM元素
- 激活CSS伪类（例如：:hover）
- 查询某些属性或调用某些方法
clientWidth、clientHeight、clientTop、clientLeft
offsetWidth、offsetHeight、offsetTop、offsetLeft
scrollWidth、scrollHeight、scrollTop、scrollLeft
scrollIntoView()、scrollIntoViewIfNeeded()
getComputedStyle()
getBoundingClientRect()
scrollTo()

这些会导致回流

 当页面中元素样式的改变并不影响它在文档流中的位置时（例如：color、background-color、visibility等），浏览器会将新样式赋予给元素并重新绘制它，这个过程称为重绘。

 回流比重绘代价高，现代浏览器的优化会维护一个队列，把所有引起回流的操作放到队列中，到达阈值会情况一次更新
 当你访问以下属性或方法时，浏览器会立刻清空队列：

```
clientWidth、clientHeight、clientTop、clientLeft

offsetWidth、offsetHeight、offsetTop、offsetLeft

scrollWidth、scrollHeight、scrollTop、scrollLeft

width、height

getComputedStyle()

getBoundingClientRect()
```
因为队列中可能会有影响到这些属性或方法返回值的操作，即使你希望获取的信息与队列中操作引发的改变无关，浏览器也会强行清空队列，确保你拿到的值是最精确的。

**避免**

* 避免使用table布局。
* 尽可能在DOM树的最末端改变class。
* 避免设置多层内联样式。
* 将动画效果应用到position属性为absolute或fixed的元素上。
* 避免使用CSS表达式例如：calc()
* 避免频繁操作样式，dom，频繁读取会引入回流，多次使用请缓存，动画绝对定位

### cookies、session、sessionStorage、localStorage（session储存于服务端，cookies存储于浏览器。本地存储有什么坑
（cookies 只有4kb，可以被浏览器带上。Local。Ios隐私模式，会报错）
Localsorage的异常处理用try catch处理
但在实际过程中甚至可能出现无法setItem()这样的低级bug。因此我建议，可以通过在try/catch结构里set/get一个测试数据有无出现异常来判断该浏览器是否支持localstorage，当然测试完后记得删掉测试数据哦。
Localstorage 在某些浏览器会有bug，比如，在iPhone/iPad上有时设置setItem()时会出现诡异的QUOTA_EXCEEDED_ERR错误，这时一般在setItem之前，先removeItem()就ok了。

### 多window tab页签之间的通信怎么做

·  window.open与window.opener （基于当前window生成子window，实现父->子window的通信）
·  localStorage与window.onstorage （监听onstorage的event对象key的变化，实现tab间通信）
·  BroadCast Channel （创建一个单独通信通道，tab在这个通道内进行通信）
·  Shared worker （开启一个共享的工作线程，tab在这个共享线程内进行通信）
例如：点击图片打开一个新的window，1s后替换成别的图片。（opener是父窗口的实例。）


### Xss攻击，反射性，储存型，dom型；
反射型：提交的不可信的数据被立刻返回（比如浏览器后面加恶意参数）。（主要是攻击者设计链接采用社会工程学手段猜用户行为）
储存型：和反射型类似，储存型sxx会持久保存于应用的储存中，常常利用后端数据库保存恶意代码，有时候会用日志文件。
DOM XSS：比如eval（）会执行恶意代码。
绕过xss防御机制：（有的利用广告动态插入脚本，利用社会工程，骗术，发邮件钓鱼攻击，网站钓鱼，）
钓鱼攻击
中间人攻击：
无线攻击：

### 事件冒泡与捕获
addEventListener第三个参数 
true - 事件句柄在捕获阶段执行（即在事件捕获阶段调用处理函数）
false- false- 默认。事件句柄在冒泡阶段执行
事件代理

### input 中如何监听值的变化
可以实时监听值的变化的事件有以下几种
keypress
keydown
keyup
input
注: onChange 无法做到实时监听，因为 onChange 需要失去焦点才能触发

### 使用ES6 的Proxy实现数组负索引。 （负索引：例如，可以简单地使用arr[-1]替代arr[arr.length-1]访问最后一个元素，[-2]访问倒数第二个元素，以此类推）
function PythonArray(arr) {
  return new Proxy(arr, {
    get(target, prop, receiver) {
      if ((key = Number.parseInt(prop))) {
        const len = Reflect.get(target, 'length', receiver);
        prop = key < 0 && Math.abs(key) <= len ? len + key : prop;
      }
      return Reflect.get(target, prop, receiver);
    },
    set(target, prop, value, receiver) {
      if ((key = Number.parseInt(prop))) {
        const len = Reflect.get(target, 'length', receiver);
        prop = key < 0 && Math.abs(key) <= len ? len + key : prop;
      }
      return Reflect.set(target, prop, value, receiver);
    },
    deleteProperty(target, prop) {
      if ((key = Number.parseInt(prop))) {
        const len = target.length;
        prop = key < 0 && Math.abs(key) <= len ? len + key : prop;
      }
      return Reflect.deleteProperty(target, prop);
    },
  });
}


## CSS
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
`white-space`控制空白字符，控制自动换行，
`word-break`控制单词如何被拆分换行碰到边界一律换行
`word-wrap`控制单词拆分换行只有长到溢出的单词会被拆分换行）          
### 什么情况会导致网页重绘，和重排，
（重绘：修改dom，修改样式表，用户事件。如何减少重绘和重排，合并dom操作和样式修改。批量修改dom，隐藏元素修改后再显示，使用文档片段doument.Fragment构建一个子树，再拷贝回文档，讲元素拷贝到一个脱离稳定的节点，在拷贝回来、动画使用定位脱离文档，css3加速）
### Css会阻塞渲染吗？
css不会阻塞dom解析，css会阻塞dom渲染，css加载会阻塞后面的js语句执行
### DOMContentLoaded方法会在什么时候执行？
（js在css前面，不会等待css加载完毕就会触发这个事件，js在css的后面会在css加载完毕执行。）
### Background书写顺序
（color ，image repeat attachment  postion）
### css 伪类与伪元素区别
1）伪类(pseudo-classes)

其核⼼就是⽤来选择DOM树之外的信息,不能够被普通选择器选择的⽂档之外的元素，⽤来添加⼀些选择器的特殊效果。
⽐如:hover :active :visited :link :visited :first-child :focus :lang等
由于状态的变化是⾮静态的，所以元素达到⼀个特定状态时，它可能得到⼀个伪类的样式；当状态改变时，它⼜会失去这个样式。
由此可以看出，它的功能和class有些类似，但它是基于⽂档之外的抽象，所以叫 伪类。
2）伪元素(Pseudo-elements)

DOM树没有定义的虚拟元素
核⼼就是需要创建通常不存在于⽂档中的元素，
⽐如::before ::after 它选择的是元素指定内容，表示选择元素内容的之前内容或之后内容。
伪元素控制的内容和元素是没有差别的，但是它本身只是基于元素的抽象，并不存在于⽂档中，所以称为伪元素。⽤于将特殊的效果添加到某些选择器
2）伪类与伪元素的区别

表示⽅法

CSS2 中伪类、伪元素都是以单冒号:表示,
CSS2.1 后规定伪类⽤单冒号表示,伪元素⽤双冒号::表示，
浏览器同样接受 CSS2 时代已经存在的伪元素(:before, :after, :first�line, :first-letter 等)的单冒号写法。
CSS2 之后所有新增的伪元素(如::selection)，应该采⽤双冒号的写法。
CSS3中，伪类与伪元素在语法上也有所区别，伪元素修改为以::开头。浏览器对以:开头的伪元素也继续⽀持，但建议规范书写为::开头
定义不同

伪类即假的类，可以添加类来达到效果
伪元素即假元素，需要通过添加元素才能达到效果
总结:

伪类和伪元素都是⽤来表示⽂档树以外的"元素"。
伪类和伪元素分别⽤单冒号:和双冒号::来表示。
伪类和伪元素的区别，关键点在于如果没有伪元素(或伪类)，
是否需要添加元素才能达到效果，如果是则是伪元素，反之则是伪类。
4）相同之处：

伪类和伪元素都不出现在源⽂件和DOM树中。也就是说在html源⽂件中是看不到伪类和伪元素的。
不同之处：
伪类其实就是基于普通DOM元素⽽产⽣的不同状态，他是DOM元素的某⼀特征。
伪元素能够创建在DOM树中不存在的抽象对象，⽽且这些抽象对象是能够访问到的。

## JS

### 对闭包的看法，为什么要用闭包？说一下闭包原理以及应用场景 
1）什么是闭包
函数执行后返回结果是一个内部函数，并被外部变量所引用，如果内部函数持有被执行函数作用域的变量，即形成了闭包。

可以在内部函数访问到外部函数作用域。使用闭包，一可以读取函数中的变量，二可以将函数中的变量存储在内存中，保护变量不被污染。而正因闭包会把函数中的变量值存储在内存中，会对内存有消耗，所以不能滥用闭包，否则会影响网页性能，造成内存泄漏。当不需要使用闭包时，要及时释放内存，可将内层函数对象的变量赋值为null。

2）闭包原理
函数执行分成两个阶段(预编译阶段和执行阶段)。

在预编译阶段，如果发现内部函数使用了外部函数的变量，则会在内存中创建一个“闭包”对象并保存对应变量值，如果已存在“闭包”，则只需要增加对应属性值即可。
执行完后，函数执行上下文会被销毁，函数对“闭包”对象的引用也会被销毁，但其内部函数还持用该“闭包”的引用，所以内部函数可以继续使用“外部函数”中的变量
利用了函数作用域链的特性，一个函数内部定义的函数会将包含外部函数的活动对象添加到它的作用域链中，函数执行完毕，其执行作用域链销毁，但因内部函数的作用域链仍然在引用这个活动对象，所以其活动对象不会被销毁，直到内部函数被烧毁后才被销毁。

3）优点
可以从内部函数访问外部函数的作用域中的变量，且访问到的变量长期驻扎在内存中，可供之后使用
避免变量污染全局
把变量存到独立的作用域，作为私有成员存在
4）缺点
对内存消耗有负面影响。因内部函数保存了对外部变量的引用，导致无法被垃圾回收，增大内存使用量，所以使用不当会导致内存泄漏
对处理速度具有负面影响。闭包的层级决定了引用的外部变量在查找时经过的作用域链长度
可能获取到意外的值(captured value)

### 原型链
每一个函数都有一个prototype属性，这个属性指向函数的原型，js创建对象会从原型继承属性
`__proto__` 这个属性会指向对象的原型
`constructor` 会指向关联的构造函数
读取实例属性，找不到会取关联的原型中找，会顺着原型链找，本质是一个复杂的链表
并不是继承，继承意味着复制操作，然而 JavaScript 默认并不会复制对象的属性，相反，JavaScript 只是在两个对象之间创建一个关联，这样，一个对象就可以通过委托访问另一个对象的属性和函数，所以与其叫继承，委托的说法反而更准确些。

### 继承
* 原型链继承 将父类的实例作为子类的原型
  - 优点：父类方法可以复用

  - 缺点：
  父类的引用属性会被所有子类实例共享
   子类构建实例时不能向父类传递参数

* 构造函数继承 将父类构造函数的内容复制给了子类的构造函数。
   - 优点：和原型链继承完全反过来。
父类的引用属性不会被共享
子类构建实例时可以向父类传递参数
  - 缺点：父类的方法不能复用，子类实例的方法每次都是单独创建的。

* 原型式继承
利用一个空对象作为中介，将某个对象直接赋值给空对象构造函数的原型。
缺点：
原型链继承多个实例的引用类型属性指向相同，存在篡改的可能。
无法传递参数

### call、apply 以及 bind 
call 和 apply 的共同点
它们的共同点是，都能够改变函数执行时的上下文，将一个对象的方法交给另一个对象来执行，并且是立即执行的。借用其他的对象方法，节省内存占用。
区别是参数区别
* 调用 call 的对象，必须是个函数 Function。
* call 的第一个参数，是一个对象。 Function 的调用者，将会指向这个对象。如果不传，则默认为全局对象 window。
* 第二个参数开始，可以接收任意个参数。每个参数会映射到相应位置的 Function 的参数上。但是如果将所有的参数作为数组传入，它们会作为一个整体映射到 Function 对应的第一个参数上，之后参数都为空。
* apply调用者必须是函数 Function，并且只接收两个参数，第一个参数的规则与 call 一致。
* apply第二个参数，必须是数组或者类数组，它们会被转换成类数组，传入 Function 中，并且会被映射到 Function 对应的参数上。这也是 call 和 apply 之间，很重要的一个区别。

bind() 方法创建一个新的函数，改变函数体内的 this 指向。不同的是，bind 方法的返回值是函数，并且需要稍后调用，才会执行。

### For in 迭代和for of区别
1.index索引为字符串型数字，不能直接进行几何运算
2.遍历顺序有可能不是按照实际数组的内部顺序
3.使用for in会遍历数组所有的可枚举属性，包括原型。所以for in更适合遍历对象，不要使用for in遍历数组。for of不能遍历对象
for in更适合遍历对象，不要使用for in遍历数组，for of遍历的只是数组内的元素

### 类数组和数组的区别，dom 的类数组如何转换成数组
数组是一个特殊对象,与常规对象的区别：
当由新元素添加到列表中时，自动更新length属性
设置length属性，可以截断数组
从Array.protoype中继承了方法
属性为'Array'
类数组是一个拥有length属性，并且他属性为非负整数的普通对象，类数组不能直接调用数组方法。
2）区别
本质：类数组是简单对象，它的原型关系与数组不同。
类数组转换为数组

转换方法
使用 Array.from()
使用 Array.prototype.slice.call()
使用 Array.prototype.forEach() 进行属性遍历并组成新的数组
转换须知
转换后的数组长度由 length 属性决定。索引不连续时转换结果是连续的，会自动补位。

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

### 使用typeof test === "object"来判定test是否是对象有什么缺陷？如何避免？
并不能准确判断test就是一个 Object。null 和array无法判断
可以通过 Object.prototype.toString.call(bar) === "[object Object]" 来避免这种弊端


### 介绍下前端加密的常见场景和方法
1. Base64 编码
    大家经常说的是 Base64 加密，有 Base64 加密吗？真木有，只有 Base64 编码。
    Base64 是一种基于 64 个可打印字符来表示二进制数据的表示方法，详见 [1]。常用于在通常处理文本数据的场合，表示、传输、存储一些二进制数据,包括 MIME 的 email，email via MIME，在 XML 中存储复杂数据；主要用来解决把不可打印的内容塞进可打印内容的需求。很多编程语言中都内置了该编码方法，因此，Base64 适用于小段内容的编码，比如数字证书签名、Cookie的内容等；而且 Base64 也是一种通过查表的编码方法，不能用于加密，如果需要加密，请使用专业的加密算法。
2. 哈希算法（Hash）
    哈希（Hash）是将目标文本转换成具有固定长度的字符串（或叫做消息摘要）。当输入发生改变时，产生的哈希值也是完全不同的。从数学角度上讲，一个哈希算法是一个多对一的映射关系，对于目标文本 T，算法 H 可以将其唯一映射为 R，并且对于所有的 T，R 具有相同的长度，所以 H 不存在逆映射，也就是说哈希算法是不可逆的。
    
    基于哈希算法的特性，其适用于该场景：被保护数据仅仅用作比较验证且不需要还原成明文形式。比较常用的哈希算法是 MD5 和 SHA1，详见 [2][3]。
    我们比较熟悉的使用哈希存储数据的例子是：当我们登录某个已注册网站时，在忘记密码的情况下需要重置密码，此时网站会给你发一个随机的密码或者一个邮箱激活链接，而不是将之前的密码发给你，这就是因为哈希算法是不可逆的。
    需要注意的是：在 Web 应用中，在浏览器中使用哈希加密的同时也要在服务端上进行哈希加密。
    现在，对于简单的哈希算法的攻击方法主要有：寻找碰撞法和穷举法。所以，为了保证数据的安全，可以在哈希算法的基础上进一步的加密，常见的方法有：加盐、慢哈希、密钥哈希、XOR 等。

3. 加盐（Adding Salt）    
加盐加密是一种对系统登录口令的加密方式，它实现的方式是将每一个口令同一个叫做“盐”（salt）的 n 位随机数相关联。
（1）盐值应该使用加密的安全伪随机数生成器（ Cryptographically Secure Pseudo-Random Number Generator，CSPRNG ）产生，比如 C 语言的 rand() 函数，这样生成的随机数高度随机、完全不可预测；
    （2）盐值混入目标文本中，一起使用标准的加密函数进行加密；
    （3）盐值要足够长（经验表明：盐值至少要跟哈希函数的输出一样长）且永不重复；
    （4）盐值最好由服务端提供，前端取值使用
    
7. 加密（Encrypt）
    不同于哈希，加密（Encrypt）是将目标文本转换成具有不同长度的、可逆的密文。也就是说加密算法是可逆的，而且其加密后生成的密文长度和明文本身的长度有关。从数学角度上讲的话： 一个加密算法是一个一对一的映射，其中第二个参数叫做加密密钥，E 可以将给定的明文 T 结合 Ke 唯一映射为密文 R，反过来，Kd 结合密文 R 也可以唯一映射为对应明文 T，其中 Kd 叫做解密密钥。

    
    

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

### new的执行过程
创建一个空对象
将对象的_proto_指向构造函数的 prototype
将这个构造函数作为这个对象的this
返回该对象

### 关于Vue.js虚拟DOM的优缺点
1）优点

保证性能下限： 框架的虚拟 DOM 需要适配任何上层 API 可能产生的操作，它的一些 DOM 操作的实现必须是普适的，所以它的性能并不是最优的；但是比起粗暴的 DOM 操作性能要好很多，因此框架的虚拟 DOM 至少可以保证在你不需要手动优化的情况下，依然可以提供还不错的性能，即保证性能的下限；
无需手动操作 DOM： 我们不再需要手动去操作 DOM，只需要写好 View-Model 的代码逻辑，框架会根据虚拟 DOM 和 数据双向绑定，帮我们以可预期的方式更新视图，极大提高我们的开发效率；
跨平台： 虚拟 DOM 本质上是 JavaScript 对象,而 DOM 与平台强相关，相比之下虚拟 DOM 可以进行更方便地跨平台操作，例如服务器渲染、weex 开发等等。
2）缺点
无法进行极致优化： 虽然虚拟 DOM + 合理的优化，足以应对绝大部分应用的性能需求，但在一些性能要求极高的应用中虚拟 DOM 无法进行针对性的极致优化。比如VScode采用直接手动操作DOM的方式进行极端的性能优化

### promise原理
 Promise 必须为以下三种状态之一：等待态（Pending）、执行态（Fulfilled）和拒绝态（Rejected）。一旦Promise 被 resolve 或 reject，不能再迁移至其他任何状态。
 在实际应用的时候，我们很容易会碰到这样的场景，不管Promise最后的状态如何，都要执行一些最后的操作。我们把这些操作放到 finally 中，也就是说 finally 注册的函数是与 Promise 的状态无关的，不依赖 Promise 的执行结果。
Promise.resolve 的入参可能有以下几种情况：

无参数 [直接返回一个resolved状态的 Promise 对象]
普通数据对象 [直接返回一个resolved状态的 Promise 对象]
一个Promise实例 [直接返回当前实例]
一个thenable对象(有then方法的对象，立即执行then方法)
Promise.all 入参是一个 Promise 的实例数组，然后注册一个 then 方法，然后是数组中的 Promise 实例的状态都转为 fulfilled 之后则执行 then 方法。

### 为什么 0.1 + 0.2 != 0.3
因为 JS 采用 IEEE 754 双精度版本（64位），并且只要采用 IEEE 754 的语言都有该问题。
小数算二进制和整数不同。乘法计算时，只计算小数位，整数位用作每一位的二进制，并且得到的第一位为最高位。所以我们得出 0.1 = 2^-4 * 1.10011(0011)，那么 0.2 的演算也基本如上所示，只需要去掉第一步乘法，所以得出 0.2 = 2^-3 * 1.10011(0011)。
回来继续说 IEEE 754 双精度。六十四位中符号位占一位，整数位占十一位，其余五十二位都为小数位。因为 0.1 和 0.2 都是无限循环的二进制了，所以在小数位末尾处需要判断是否进位（就和十进制的四舍五入一样）。
所以 2^-4 * 1.10011...001 进位后就变成了 2^-4 * 1.10011(0011 * 12次)010 。那么把这两个二进制加起来会得出 2^-2 * 1.0011(0011 * 11次)0100 , 这个值算成十进制就是 0.30000000000000004
下面说一下原生解决办法，如下代码所示
parseFloat((0.1 + 0.2).toFixed(10))


### 如何给fetch增加超时时间
（用promise模拟）

### innerHTML和outHTML的区别
 * innerHTML设置或获取于对象起始和结束标签内的HTML
 * outerHTML设置或获取对象以及起内容的HTML形式

### innerText和textContent的区别
innerText的值依赖于浏览器的显示，textContent依赖于代码的显示
如果一个元素之间包含了script标签或者style标签，innerText是获取不到这两个元素之间的文本的，而textContent可以
textContent会把空标签解析成换行
innerText只会把block元素类型的空标签解析换行，并且如果是多个的话仍看成是一个，而inline类型的原素则解析成空格
innerText的设置会引发浏览器的回流操作，而textContent则不一定会

### js事件循环
js单线程 同步执行任务，异步任务有异步队列，会将事件挂起，等主线程空闲执行，会队列中的任务一次取出，
异步任务执行优先级有区别，macro task与micro task
以下事件属于宏任务：
`setInterval()`
`setTimeout()`
以下事件属于微任务
`new Promise()`
`new MutaionObserver()`
执行完任务队列头的宏任务后就开始执行微任务队列中的微任务，直到微任务队列为空。

### node事件循环

* 应用层：   即 JavaScript 交互层，常见的就是 Node.js 的模块，比如 http，fs
* V8引擎层：  即利用 V8 引擎来解析JavaScript 语法，进而和下层 API 交互
* NodeAPI层：  为上层模块提供系统调用，一般是由 C 语言来实现，和操作系统进行交互 。
* LIBUV层： 是跨平台的底层封装，实现了 事件循环、文件操作等，是 Node.js 实现异步的核心 。

### 如何前端进行代码检测
（圈复杂度(Cyclomatic complexity)描写了代码的复杂度，可以理解为覆盖代码所有场景所需要的最少测试用例数量。CC 越高，代码则越不好维护）

### 你的前端项目资源缓存配置策略
（ 2个指标，静态资源的加载速度，页面渲染速度，
1.html是不能缓存的，设置极短的max-age的值，或者设置cache-control：no-cache
2。js css img文件
通过版本控制，wenpack打包生成hash值，每次打包才会改变。可以给http header设置较大的缓存时间 ，避免304请求和服务器进行进球链接 

### web font 网页字体
浏览器在DOMNode的CSS选择器中发现@font-face时才会下载web fonts文件，这个时候浏览器已经下载完成html/css/js文件；
如果在浏览器发现需要加载font文件之前就告诉浏览器下载font文件，会加快文件下载和页面加载速度。
静态资源加http headers缓存。页面关键文件，路由文件可以做预加载，就是在首屏加载完毕的时候预先加载路由文件。

### 什么是 Open Graph 协议，用来做什么
是一套开放的网页标注协议，通过 meta 标签标注网页的类型

### SVG图标颜色文字继承与填充
svg { fill: #369; }

## VUE
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

### 既然 Vue 通过数据劫持可以精准探测数据在具体dom上的变化,为什么还需要虚拟 DOM diff 呢
前置知识: 依赖收集、虚拟 DOM、响应式系统

现代前端框架有两种方式侦测变化，一种是 pull ，一种是 push

pull: 其代表为React，我们可以回忆一下React是如何侦测到变化的,我们通常会用setStateAPI显式更新，然后React会进行一层层的Virtual Dom Diff操作找出差异，然后Patch到DOM上，React从一开始就不知道到底是哪发生了变化，只是知道「有变化了」，然后再进行比较暴力的Diff操作查找「哪发生变化了」，另外一个代表就是Angular的脏检查操作。

push: Vue的响应式系统则是push的代表，当Vue程序初始化的时候就会对数据data进行依赖的收集，一但数据发生变化,响应式系统就会立刻得知。因此Vue是一开始就知道是「在哪发生变化了」，但是这又会产生一个问题，如果你熟悉Vue的响应式系统就知道，通常一个绑定一个数据就需要一个Watcher
一但我们的绑定细粒度过高就会产生大量的Watcher，这会带来内存以及依赖追踪的开销，而细粒度过低会无法精准侦测变化,因此Vue的设计是选择中等细粒度的方案,在组件级别进行push侦测的方式,也就是那套响应式系统,通常我们会第一时间侦测到发生变化的组件,然后在组件内部进行Virtual Dom Diff获取更加具体的差异，而Virtual Dom Diff则是pull操作，Vue是push+pull结合的方式进行变化侦测的。

面试官的意思是：假设有一个 input ，通过 v-model 双向绑定了 data.form.value ，当 data.form.value 的 setter 触发时，直接操作 dom：input.value = mValue 就行了，为啥还需要 vdom ？

答案：
1）应用不可能只有表单控件值改变，还有其他的元素的改动，难道也要在 setter 里面自己做吗？MVVM 重回 MVC
2）vdom 实现的批量 dom 更新可以提供一个可靠的 dom 改动性能下限
3）代码维护性天壤之别



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
 * 尽量减少data中的数据，data中的数据都会增加getter和setter，会收集对应的watcher
 * v-if和v-for不能连用
 * 如果需要使用v-for给每项元素绑定事件时使用事件代理
 * SPA 页面采用keep-alive缓存组件
 * 在更多的情况下，使用v-if替代v-show
 * key保证唯一
 * 使用路由懒加载、异步组件
 * 防抖、节流
 * 第三方模块按需导入
 * 长列表滚动到可视区域动态加载
 * 图片懒加载
 * Tree shaking webpack 构建重要的一部分,清除项目中无用代码(webpack 4+自动开启摇树)
 * Split chunks 按需加载
 * 拆包将项目用到的react的包放到cdn,每次拉取react资源可以强制命中缓存
 * 经常重构删除多余重复代码
 * 后端必备gzip

## webpack
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

### webpack 钩子
webpack的插件机制就是在每一次编译过程中的某个时间节点做一些处理，plugin针对关键时间点如下:
afterEmit	资源输出到目录完成	compilation	异步
afterPlugins	启动一次新的编译	compiler	同步
compilation	compilation对象创建完成	compilation	同步
compile	创建compilation对象之前	compilationParams	同步
done	完成编译	stats	同步
emit	资源生成完成，输出之前	compilation	异步


## 其他
### 为什么要使用pm2
对于这个问题，先说说我的看法，最基本的原因是因为node本身是一个单线程应用，它的特点就是所有方法都是串行一次执行，并且node并没有能力像Java一样独自去创建一个新的线程来实现异步操作，如果在执行I/O中遇到了阻塞就会降低整个应用的执行效率，导致CPU使用率高等不利原因。
因此在这种模式下，一个线程只能处理一个任务，要想提高吞吐量必须通过多线程。虽然单线程的好处有很多比如避免了线程同步或者死锁、状态同步等等之类的问题，但是在应用和计算能力要求日益倍增的今天，单线程最大的弊端就是无法利用多核CPU带来的优势来提升运行效率。
PM2是具有内置负载平衡器的Node.js / io.js应用程序的生产过程管理器。它使您可以使应用程序永远保持活动状态，无需停机即可重新加载它们，并简化常见的系统管理任务

### 什么是服务端渲染
客户端渲染时由客户端的js控制的,服务端时服务端返回的字符串
同构.,服务端完成页面结构,但是事件需要在客户端绑定
服务端store共享数据,应该时每人一份.createSrore应该为函数
在服务端渲染中，有两种页面渲染的方式：

 * 前端服务器通过请求后端服务器获取数据并组装HTML返回给浏览器，浏览器直接解析HTML后渲染页面
 * 浏览器在交互过程中，请求新的数据并动态更新渲染页面

这两种渲染方式有一个不同点就是，一个是在服务端中组装html的，一个是在客户端中组装html的，运行环境是不一样的。所谓同构，就是让一份代码，既可以在服务端中执行，也可以在客户端中执行，并且执行的效果都是一样的，都是完成这个html的组装，正确的显示页面。也就是说，一份代码，既可以客户端渲染，也可以服务端渲染。

同构应用来说，我们必须实现客户端与服务端的路由、模型组件、数据模型的共享。

通过React提供的服务端渲染方法，我们可以在服务器上生成DOM结构，让用户尽早看到页面内容，但是一个能够工作的页面不仅仅是DOM结构，
还包括了各种事件响应、用户交互。那么意味着，在客户端上，还得执行一段JS代码绑定事件、处理异步交互，在React中，意味着整个页面的组
件需要重新渲染一次，反而带来了额外的负担。因此，在服务端渲染中，有一个十分重要的概念， 同构(Isomorphic) ，在服务端和客户端中，使
用完全一致的React组件，这样能够保证两个端中渲染出的DOM结构是完全一致的，而在这种情况下，客户端在渲染过程中，会判断已有的DOM结
构是否和即将渲染出的结构相同，若相同，不重新渲染DOM结构，只是进行事件绑定。在同构应用中，一套代码（不局限于组件），能够同时在客
户端和服务端运行


### ts 的as const 什么意思
为了解决let赋值问题的，将一个mutable的变量改为readonly。
避免将类型推断为联合类型。
但我们可以通过添加一个 const assertion 来解决redux里面action的类型严格为声明的type而不是字符串

### 如何在https里面发送http请求 
img
加上
```
<meta http-equiv="Content-Security-Policy" content="upgrade-insecure-requests" />
```
即可

### 现在有多个spa的项目，有angular的，有vue的和react的，如何将他们合并成一个大统一的spa项目
微前端
iframe

##node
### node 引入一个模块的过程是什么
 路径分析 1判断内置模块  2路径形式的文件模块，./..相对路径模块和/绝对路径模块 3自定义模块 通过Module._resolveLookupPaths方法生成node_modules可能存在的路径

 2路径解析 列出所有可能的后缀名 绝对路径不再搜索  判断目录是否有斜杠，
 查询缓存（将request和paths通过\x00（这是空格） 合成cacheKey） 判断是否查找过
遍历patch是将path 与request组成文件路径 basePath
如果 basePath 存在则调用 fs.realPathSync获取文件真实路径
将文件真实路径缓存到 Module._pathCache（key 就是前面生成的 cacheKey）
fs.realPathSync
查询缓存 （缓存key为p , Module._findPath 中生成的文件路径）
从左往后遍历路径字符串 查询到 / 时，拆分路径， 判断该路径为软连接，如果时软链接则查询真实链接。并重新生成路径怕，继续向后遍历， 这里有一个细节
遍历过程中生成的子路径base会缓存在knownHard 和cache 避免重复查询
遍历完成得到模块对应的真实路径，此时会将原始路径priginal 作为key 真实路径作为value，保存在缓存
require,resolve.paths 等价于 Modules._resolveLookuoPaths 获取所有node_modules可能存在路径
查询缓存 如果路径为 / 直接返回 [‘/node_modules’]

### 如何封装node中间件
在NodeJS中，中间件主要是指封装所有Http请求细节处理的方法。一次Http请求通常包含很多工作，如记录日志、ip过滤、查询字符串、请求体解析、Cookie处理、权限验证、参数验证、异常处理等，但对于Web应用而言，并不希望接触到这么多细节性的处理，因此引入中间件来简化和隔离这些基础设施与业务逻辑之间的细节，让开发者能够关注在业务的开发上，以达到提升开发效率的目的。

中间件的行为比较类似Java中过滤器的工作原理，就是在进入具体的业务处理之前，先让过滤器处理。

### node 中间层怎样做的请求合并转发
1） 什么是中间层

就是前端---请求---> nodejs ----请求---->后端 ----响应--->nodejs--数据处理---响应---->前端。这么一个流程，这个流程的好处就是当业务逻辑过多，或者业务需求在不断变更的时候，前端不需要过多当去改变业务逻辑，与后端低耦合。前端即显示，渲染。后端获取和存储数据。中间层处理数据结构，返回给前端可用可渲染的数据结构。
nodejs是起中间层的作用，即根据客户端不同请求来做相应的处理或渲染页面，处理时可以是把获取的数据做简单的处理交由底层java那边做真正的数据持久化或数据更新，也可以是从底层获取数据做简单的处理返回给客户端。
通常我们把Web领域分为客户端和服务端，也就是前端和后端，这里的后端就包含了网关，静态资源，接口，缓存，数据库等。而中间层呢，就是在后端这里再抽离一层出来，在业务上处理和客户端衔接更紧密的部分，比如页面渲染（SSR），数据聚合，接口转发等等。
以SSR来说，在服务端将页面渲染好，可以加快用户的首屏加载速度，避免请求时白屏，还有利于网站做SEO，他的好处是比较好理解的。
2）中间层可以做的事情

代理：在开发环境下，我们可以利用代理来，解决最常见的跨域问题；在线上环境下，我们可以利用代理，转发请求到多个服务端。
缓存：缓存其实是更靠近前端的需求，用户的动作触发数据的更新，node中间层可以直接处理一部分缓存需求。
限流：node中间层，可以针对接口或者路由做响应的限流。
日志：相比其他服务端语言，node中间层的日志记录，能更方便快捷的定位问题（是在浏览器端还是服务端）。
监控：擅长高并发的请求处理，做监控也是合适的选项。
鉴权：有一个中间层去鉴权，也是一种单一职责的实现。
路由：前端更需要掌握页面路由的权限和逻辑。
服务端渲染：node中间层的解决方案更灵活，比如SSR、模板直出、利用一些JS库做预渲染等等。
3）node转发API（node中间层）的优势

可以在中间层把java|php的数据，处理成对前端更友好的格式
可以解决前端的跨域问题，因为服务器端的请求是不涉及跨域的，跨域是浏览器的同源策略导致的
可以将多个请求在通过中间层合并，减少前端的请求
4）如何做请求合并转发

使用express中间件multifetch可以将请求批量合并
使用express+http-proxy-middleware实现接口代理转发

### 不使用用第三方模块手动实现一个nodejs代理服务器，实现请求合并转发、

1.实现思路

①搭建http服务器，使用Node的http模块的createServer方法
②接收客户端发送的请求，就是请求报文，请求报文中包括请求行、请求头、请求体
③将请求报文发送到目标服务器，使用http模块的request方法

第一步：http服务器搭建
第二步：接收客户端发送到代理服务器的请求报文
这一步主要数据在客户端到服务器端进行传输时在nodejs中需要用到buffer来处理一下。处理过程就是将所有接收的数据片段chunk塞到一个数组中，然后将其合并到一起还原出源数据。合并方法需要用到Buffer.concat，这里不能使用加号，加号会隐式的将buffer转化为字符串，这种转化不安全。
第三步：使用http模块的request方法，将请求报文发送到目标服务器
第二步已经得到了客户端上传的数据，但是缺少请求头，所以在这一步根据客户端发送的请求需要构造请求头，然后发送

