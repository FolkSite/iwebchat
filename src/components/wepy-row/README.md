## Layout 布局

### 使用指南
在 app.wxss 中引入组件库所有样式
```css
@import "path/to/zanui-weapp/dist/index.wxss";
```

### 代码演示
Layout 组件提供了24列栅格，添加 dj-col-x 可以设置元素所占宽度
```html
<view class="dj-row">
  <view class="dj-col dj-col-8">
    span: 8
  </view>
  <view class="dj-col dj-col-8">
    span: 8
  </view>
  <view class="dj-col dj-col-8">
    span: 8
  </view>
</view>
```

Layout 提供了 offset 功能。添加 dj-col-offset-x 类可以设置列的偏移宽度，计算方式与 span 相同
```html
<view class="dj-row">
  <view class="dj-col dj-col-4">span: 4</view>
  <view class="dj-col dj-col-10 dj-col-offset-4">offset: 4, span: 10</view>
</view>
<view class="dj-row">
  <view class="dj-col dj-col-12 dj-col-offset-12">offset: 12, span: 12</view>
</view>
```
