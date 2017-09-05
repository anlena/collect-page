* 判断阻止默认事件

  ```js
  body.addEventListener('click',function(e) {
  	e = e || window.event;
  	var target = e.target || e.srcElement;
  	if(target != block){
  		api.closeWin({
  		});
  	}

  },false);
  ```

* 循环监听js事件

  ```js
  var list_obj = document.getElementsByTagName('li');  
  for (var i = 0; i <= list_obj.length; i++) {      
    (function(){      
      var p = i     
      list_obj[i].onclick = function() {      
        alert(p);      
      }  
    })();  
  }  
  ```


