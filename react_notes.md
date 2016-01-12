# Kick Start React

Author: Lin Dong

Date: Sun Jan 10 14:42:33 PST 2016

## What is React?
React was developed and used by Facebook starting 2013. React is simple, declarative and composable view-only JavaScript library. If you are familiar with MVC framework, then React is the view part.

### Show Cases
Facebook, Instagram, WalMart, Wordpress, and [More](http://builtwithreact.io/)

## Why use it?
React is simple, declarative and composable view-only JavaScript library.

Using JavaScript to manipulate DOM is Slow is slow
![](http://www.phpied.com/wp-content/uploads/2009/12/domlandia.png)

By implementing and leverage [virtual dom](http://tonyfreed.com/blog/what_is_virtual_dom), React can change the parts that need to be changed and then save to the real DOM tree.
![](http://calendar.perfplanet.com/wp-content/uploads/2013/12/vjeux/6.png)

What makes it really fast is:

1. Efficient diff algorithms.
2. Batching DOM read/write operations.
3. Efficient update of sub-tree only.

## How to use it?

Using React

1. Must include these two libraries in order to use React

  ```javascript
  https://fb.me/react-0.14.6.js
  https://fb.me/react-dom-0.14.6.js

  ```

2. It is essential to know JSX but not require. Optional if not using JSX, [jsfiddle sample](https://jsfiddle.net/reactjs/69z2wepo/)

  ```javascript
  https://cdnjs.cloudflare.com/ajax/libs/babel-core/5.8.24/browser.js
  ```

3. https://jsfiddle.net/ldong/apao5wse/3/

  ```javacsript

  ```


* [React JSFiddle with JSX](https://jsfiddle.net/reactjs/69z2wepo/)
* [React JSFiddle without JSX](https://jsfiddle.net/reactjs/5vjqabv3/)
* [w/ and w/o JSX side by side](http://tinyurl.com/j8ahhyt)
* [HTML to JSX](https://facebook.github.io/react/html-jsx.html)

## Demo


# Reference
* [React](https://facebook.github.io/react/index.html)
* [Babel](www.babeljs.io/repl)
* [Perf Benchmark](http://www.domgan.com/benchmark/)
* [DOM access optimization](http://www.phpied.com/dom-access-optimization/)
* [High Performance JavaScript By Zakas p37](http://shop.oreilly.com/product/9780596802806.do)
* [React Component Specs and Lifecycle](http://facebook.github.io/react/docs/component-specs.html)
* [React’s diff algorithm](http://calendar.perfplanet.com/2013/diff/)
* [The difference between Virtual DOM and DOM](http://reactkungfu.com/2015/10/the-difference-between-virtual-dom-and-dom/)
* [为什么说 DOM 操作很慢](https://leozdgao.me/why-dom-slow/)
* [React源码剖析系列 － 生命周期的管理艺术 - pure render - 知乎专栏](http://zhuanlan.zhihu.com/purerender/20312691)
* [React为什么这么火](http://www.dang-jian.com/labs/why-react/#/title)
* [React JS Tutorial and Guide to the Gotchas](https://zapier.com/engineering/react-js-tutorial-guide-gotchas/)
