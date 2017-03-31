#### this is a react Lightbox
`npm install rc-lightbox`

`import Lightbox from 'rc-lightbox'`

| isOpen | imgSource | currentImage  | onClose |
|--------|--------|----------|--------------|-------------|
|    Boolean false    |   Array 数组[{src:'http://imageUrl'}]    |  Number 当前的第几张图片 | Function 关闭

```
<Lightbox
        imgSource={this.state.lightboxImgData}
        isOpen={this.state.lightboxIsOpen}
        currentImage = {this.state.currentImage}
        onClose={this.closeLightBox}
      />
```