# \<item-carousel\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/marksmits/item-carousel)

The `<item-carousel>` is looping a large item lists horizontal. Optionally
images can be lazy image loaded using the `<img-lazy>` element.

Both elements are plain vanilla js.

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="item-carousel.html">
    <link rel="import" href="img-lazy.html">
    <style>
      .item {
        display: flex;
        flex-direction: column;
        justify-content: center;
        vertical-align: middle;
        text-align: center;
        min-height: 8rem;
        position: relative;
      }

      .item img-lazy {
        width: 4rem;
        margin: .5rem 1.5rem;
        align-self: center;
        vertical-align: middle;
      }

      .item.wide img-lazy {
        width: 5rem;
      }

      .item span {
        display: block;
        position: absolute;
        bottom: 0;
        width: 100%;
        white-space: nowrap;
        overflow: hidden;
        font-size: 0.8rem;
        color: #999;
      }
    </style>
    <item-carousel>
      <div class="item"><img-lazy srcUrl="demo/images/Ant1.svg"></img-lazy><span>Ant 1</span></div>
      <div class="item"><img-lazy srcUrl="demo/images/CBC.svg"></img-lazy><span>CBC</span></div>
      <div class="item wide"><img-lazy srcUrl="demo/images/FOX.svg"></img-lazy><span>Fox</span></div>
      <div class="item"><img-lazy srcUrl="demo/images/Globo.svg"></img-lazy><span>Globo</span></div>
      <div class="item"><img-lazy srcUrl="demo/images/Nine.svg"></img-lazy><span>Nine</span></div>
      <div class="item wide"><img-lazy srcUrl="demo/images/TF1.svg"></img-lazy><span>TF1</span></div>
      <div class="item wide"><img-lazy srcUrl="demo/images/vtm.svg"></img-lazy><span>VTM</span></div>
      <div class="item"><img-lazy srcUrl="demo/images/RTP.svg"></img-lazy><span>RTP</span></div>
      <div class="item wide"><img-lazy srcUrl="demo/images/ProTV.svg"></img-lazy><span>Pro TV</span></div>
    </item-carousel>
  </template>
</custom-element-demo>
```
-->

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
