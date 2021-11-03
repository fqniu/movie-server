## 安装依赖 npm i

```js
运行npm run start
```



## 接口如下

```js
http://localhost:9000/movie/city
http://localhost:9000/movie/swiper

```

```js
http://localhost:9000/movie/coming/?limit=10&offset=0
// limit每次请求的页面数量，offset每次请求的页面页数
```

```js
http://localhost:9000/movie/hot/?city=bj
// 参数说明: city可以为bj、sh、gz

http://localhost:9000/movie/cinema/?city=bj
// 参数说明: city可以为bj、sh、gz
```

```js
http://localhost:9000/movie/info/?name=ndmz
// 参数说明: name 
```