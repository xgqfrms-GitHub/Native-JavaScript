# for in

https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Statements/for...in

http://www.webhek.com/post/javascript-loop-foreach-for-in-for-of.html
JavaScript里的循环方法：forEach，for-in，for-of

http://wiki.jikexueyuan.com/project/javascript-garden/object/forinloop.html

http://www.infoq.com/cn/articles/es6-in-depth-iterators-and-the-for-of-loop

https://www.ibm.com/developerworks/cn/java/j-forin.html


https://gist.github.com/xgqfrms-GitHub/c2a887477b79d2b940e78723cbfafcf0


```html

    <script>
        let btns = document.querySelectorAll("button");
        // console.log(btns);
        // for (var i = 0; i < btns.length; i++) {
        //     btns[i].addEventListener("click", () => {
        //         console.log(btns[i]);
        //         console.log(btns[i].innerHTML);
        //         console.log(btns[i].innerText);
        //     });
        // }
        /*for(let i in btns){
            console.log(btns[i]);
        }
        for(let i of btns){
            console.log(btns[i]);
        }*/
        // btns.forEach((i) => {
        //     console.log(btns[i]);
        // });
        btns.forEach(function (value) {
            console.log(value);
        });
    </script>
    
``` 

http://www.infoq.com/cn/articles/es6-in-depth-iterators-and-the-for-of-loop

```
btns[0].outerHTML
//"<button>充值</button>"
btns[0].innerHTML
//"充值"
btns[0].innerText
//"充值"

```


