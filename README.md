# QuickTags
Javascript Frontend framework for DOM Elements, Events and etc.

### Example (Javascript & jQuery)

```javascript
   $(document.body).tags({
                     'div.btn':{
                         $:{
                             text:'Button A',
                             attr:{
                                 data:'demo attr'
                             },
                             event:{
                                 click:function(){
                                     alert('Clicked : Button A');
                                 },
                                 mousedown:function(){
                                     alert('Mousedown : Button A');
                                 }
                             }
                         }
                     },'.btn':{
                        $:{
                            text:'Button B',
                            event:{
                                mousedown:function(){
                                    alert('Mousedown : Button B');
                                }
                            }
                        }
                     }
                });
```
