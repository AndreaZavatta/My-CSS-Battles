# Battle #1 - Pilot Battle

## #12 - Wiggly Moustache

[Link to the problem](https://cssbattle.dev/play/12)

![result](./images/12_wiggly-moustache.png)

```html
<div class="curvetemp curve1 pos1"></div>
<div class="curvetemp curve2"></div>
<div class="curvetemp curve1 pos2"></div>
<div class="point pos1"></div>
<div class="point pos2"></div>
<style>
  body{
    background: #F5D6B4;
    display: flex;
    justify-content:center;
    align-items:center;
    
  }
  div{
    position:absolute;
  }
  .curvetemp{
    width: 60px;
    height: 60px;
    border-radius:50%;
    border-left:20px solid #D86F45;
    border-bottom:20px solid #D86F45;
    border-top: 20px solid transparent;
    border-right: 20px solid transparent;
    background: transparent;
  }
  .curve1{
    transform:rotate(-45deg);
  }
  .curve2 {
    top:100px;
    transform:rotate(135deg);
  }
  .pos1 {
    left:70px;
  }

  .pos2 {
    right:70px;
  }
  .point{
    width: 20px;
    height: 20px;
    border-radius:50%;
    background: #D86F45;
  }
</style>
```
