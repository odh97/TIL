# TIL

### Hello



### 마크다운 연습
<br/>
<br/>
<br/>
<br/>

```html
 <div>
    <a href="www.naver.com">마크다운 연습</a>
 </div>
```

<br/>
<br/>
<br/>


```javascript
    $(".btn_box .prev").on("click",function(){
        if(ww<padSize) return false;//태블릿 사이즈 끄기

        //오른쪽
        leftmove--;
        $(".brand_visual_list ul").stop().animate({"left":ul_basic-(-liww*leftmove)+"%"},300);

        if(leftmove == -8){
            leftmove = 0;
            $(".brand_visual_list ul").stop().css({"left":ul_basic+"%"});
        }

    });
```