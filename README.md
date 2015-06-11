# autocomplete2

---

A nice CMD module.

---

## Usage
[基于bigautocomplete优化](http://bigui4.sinaapp.com/autocomplete/demo.html)
It is very easy to use this module.

````html
<input type="text" id="qq" style="width:300px;"/>
````

```javascript
$(function(){
            $("#qq").bigAutocomplete({
            data:[
                { pinyin:"gpy" , code: "000001" ,title:"股票一",result:"股票一"},
                { pinyin:"gpe" , code: "000002" ,title:"股票二",result:"股票二"},
                { pinyin:"gps" , code: "000003" ,title:"股票三",result:"股票三"},
                { pinyin:"gps" , code: "000004" ,title:"股票四",result:"股票四"},
            ],
            key: ["pinyin","code"],
            value: ["code","pinyin"],
            callback:function(data){
                
            }
        }); 
})
```

## Api

Here is some details.
