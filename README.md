# tibosi

```
1.登陆地址: https://xxy.tibosi.com/login.html
2.获取试卷:

var result = [];
document.querySelectorAll("[data-paperid]").forEach(function(item) {
    result.push({
        id: item.getAttribute("data-paperid"),
        name: item.querySelector(".examName").innerHTML
    });
});
completion(result);

3.查看试卷: https://d5c3ae8.github.io/tools/tibosi.html?id=
```
