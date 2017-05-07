# BPRefresh

> a pull to refresh ripple animate plugin

> 一个水波纹效果的下拉刷新插件

### How to use
 
```
<div id="demo" class="demo">
    <div class="BPRefresh__content">
        <div class="demo__el"></div>
    </div>
</div>
``` 
    
```
<script type="text/javascript">
    new BPRefresh({
        el: 'demo',
        loading: 'img/loading.svg',
    }, function(reset) {
        var tempEl = document.createElement('div');
        tempEl.className = 'demo__el';
        document.getElementsByClassName('BPRefresh__content')[0].appendChild(tempEl);
        reset();
    });
</script>
```
