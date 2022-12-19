# Battle #2 - Visibility

## #14 - Web Maker Logo

[Link to the problem](https://cssbattle.dev/play/16)

![result](./images/16_eye-of-the-tiger.png)

```html
<div class="b"></div>
<div class="a"></div>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #0B2429;
  }
  div {
    position: absolute;
  }
  .a {
    border-radius: 50%;
    width: 50px;
    height: 50px;
    background: #0B2429;
    border: 45px solid #F3AC3C;
    outline: 20px solid #0B2429;
  }
  .b {
    border-radius: 50% 0;
    width: 200px;
    height: 200px;
    background: #998235;
    transform: rotate(45deg);
  }
</style>
```