# @gurinder/vue-progress

Vue progress bar component
Inspired by https://codepen.io/Thibaut/pen/DcEzG

### Usage
```js
import ProgressBar from '@gurinder/vue-progress';
Vue.component('progress-bar', ProgressBar);
```

```html
<progress-bar :progress="progress"></progress-bar>
```

```css
// https://codepen.io/Thibaut/pen/DcEzG
.progress {
  overflow: hidden;
  margin: 0 auto;
  width: 100%
}

.progress-val {
  float: right;
  margin-left: 15px;
  font: bold 15px/34px Helvetica, Arial, sans-serif;
  color: #333;
  text-shadow: 0 1px rgba(255, 255, 255, 0.6);
}

.progress-bar {
  display: block;
  overflow: hidden;
  height: 8px;
  //margin: 13px 0;
  background: #b8b8b8;
  border-radius: 4px;
  background-image: -webkit-linear-gradient(top, rgba(0, 0, 0, 0.2), transparent 60%);
  background-image: -moz-linear-gradient(top, rgba(0, 0, 0, 0.2), transparent 60%);
  background-image: -o-linear-gradient(top, rgba(0, 0, 0, 0.2), transparent 60%);
  background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.2), transparent 60%);
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.2), 0 1px rgba(255, 255, 255, 0.6);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.2), 0 1px rgba(255, 255, 255, 0.6);
}

.progress-in {
  display: block;
  min-width: 8px;
  height: 8px;
  background: #1997e6;
  background-image: -webkit-linear-gradient(top, rgba(255, 255, 255, 0.3), rgba(255, 255, 255, 0) 60%, rgba(0, 0, 0, 0) 61%, rgba(0, 0, 0, 0.2)), -webkit-linear-gradient(left, #147cd6, #24c1fc);
  background-image: -moz-linear-gradient(top, rgba(255, 255, 255, 0.3), rgba(255, 255, 255, 0) 60%, rgba(0, 0, 0, 0) 61%, rgba(0, 0, 0, 0.2)), -moz-linear-gradient(left, #147cd6, #24c1fc);
  background-image: -o-linear-gradient(top, rgba(255, 255, 255, 0.3), rgba(255, 255, 255, 0) 60%, rgba(0, 0, 0, 0) 61%, rgba(0, 0, 0, 0.2)), -o-linear-gradient(left, #147cd6, #24c1fc);
  background-image: linear-gradient(to bottom, rgba(255, 255, 255, 0.3), rgba(255, 255, 255, 0) 60%, rgba(0, 0, 0, 0) 61%, rgba(0, 0, 0, 0.2)), linear-gradient(to right, #147cd6, #24c1fc);
  border-radius: 4px;
  -webkit-box-shadow: inset 0 1px rgba(0, 0, 0, 0.2), inset 0 0 0 1px rgba(0, 0, 0, 0.2);
  box-shadow: inset 0 1px rgba(0, 0, 0, 0.2), inset 0 0 0 1px rgba(0, 0, 0, 0.2);
}
```