# Test1

요 파일들을 정숙이가 test 를 위한 파일들입니다. 주로 git 과 glup 를 위한 것입니다.

## git

 * **git:** git 을 이해하고 github 에 파일 올려보기 [this speed test](http://jsperf.com/katex-vs-mathjax/).
 * **ignore:** ignore 파일 적용하고 추가해보기 [site](https://www.gitignore.io/).


## gulp



```html
npm init
--> package.json

npm install gulp -g
--> 잘 모르겠음. 뭐가 막 나옴.

npm install gulp --save-dev
--> node_modules 폴더 생김.
ex> npm install gulp-[plugin name] --save-dev


gulp.task(name, deps, func)

```

#### In-browser rendering

Call `katex.render` with a TeX expression and a DOM element to render into:

```js
katex.render("c = \\pm\\sqrt{a^2 + b^2}", element);
```

If KaTeX can't parse the expression, it throws a `katex.ParseError` error.

#### Server side rendering or rendering to a string

To generate HTML on the server or to generate an HTML string of the rendered math, you can use `katex.renderToString`:

```js
var html = katex.renderToString("c = \\pm\\sqrt{a^2 + b^2}");
// '<span class="katex">...</span>'
```
