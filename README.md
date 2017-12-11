# \<item-carousel\>

The `<item-carousel>` is looping a large item lists horizontal. Optionally
images can be lazy image loaded using the `<img-lazy>` element.

Both elements are plain vanilla js.

```html
<item-carousel speed="30">
  <div class="item"><img-lazy srcUrl="images/x.svg"></img-lazy><span>name x</span></div>
  <div class="item wide"><img-lazy srcUrl="images/x.svg"></img-lazy><span>name x</span></div>
  <div class="item"><img-lazy srcUrl="images/x.svg"></img-lazy><span>name x</span></div>
  <div class="item"><img-lazy srcUrl="images/x.svg"></img-lazy><span>name x</span></div>
  ...
</item-carousel>
```

## Viewing Documentation and demo

Serve the carousel element locally.

```
$ npm install
$ polymer serve
```
