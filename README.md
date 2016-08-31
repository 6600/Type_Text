

|      属性     |     含义      |      初始值     |    重要性      |
| ------------- |:-------------:| ------------- |:-------------:|
| whatToType     |打字的文本 |  无     |必须 | 
| typeSpeed     | 打字延迟      | 250     |非必须 | 
| breakLines | 是否多行？     | true     |非必须 | 
| lifeLike | 是否以自然的方式打字      | true     |非必须 | 
| showCursor | 是否现实鼠标指针    | true     |非必须 | 
| breakWait |遇到新段落打字的延迟     | 500     |非必须 | 
| delayStart | 起始打字的延迟     | 100     |非必须 | 


##调用示例
```javascript
    <script src="jquery-2.1.4.min.js"></script>
    <script src="typeit.min.js"></script>
    <script>
    	$('#lala').typeIt({
			whatToType: ["你是一个好人.", "但是...."],//打字的文本
			typeSpeed: 250,//打字延迟
			breakLines: true,//是否多行？
			lifeLike: true,//是否以自然的方式打字
			showCursor: true,//是否现实鼠标指针
			breakWait:500,//遇到新段落打字的延迟
			delayStart:100//起始打字的延迟
		},function(){console.log("打字完成！");});
    </script>
```
![mahua](http://myweb-10017157.file.myqcloud.com/gif/131171283910969903.gif)
