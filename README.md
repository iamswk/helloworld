# helloworld

```
var arr=[105, 97, 109, 115, 119, 107, 49, 57, 57, 57, 121, 117, 101, 114, 101, 110, 56, 57, 53, 53, 51, 97, 116, 49, 54, 51, 100, 111, 116, 99, 111, 109, 122, 110, 55, 55, 53, 56];
arr中强大的map,forEach,sort,filter函数
//arr.map(function(i){ return String.fromCharCode(i); });
//排序 在原来的arr上排序
var arr1=arr.sort(function(a,b){ return a-b;});
//倒序 在原来的arr上倒序 
var arr2=arr.reverse();
//转换 创建新的arr
var arr3= arr2.map(function(i){ return String.fromCharCode(i); });
//转换数字  创建新的arr
var arr4=arr3.map(function(i){ return i.charCodeAt(0); });
```
