# BPRefresh

> a pull to refresh ripple animate plugin

### How to use
 
```
<div id="demo" class="demo">
    <div class="BPRefresh__content">
        <div class="demo__el"></div>
    </div>
</div>
``` 
    
```
    new BPRefresh({
        el: 'demo',
        loading: 'img/loading.svg',
    }, function(reset) {
        var tempEl = document.createElement('div');
        tempEl.className = 'demo__el';
        document.getElementsByClassName('BPRefresh__content')[0].appendChild(tempEl);
        reset();
    });
```
