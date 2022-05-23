# flex

## justify-between & items-center & wrap

```css
.between-center-wrap {
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
```

## row-reverse

```css
.flex-direction-row-reverse {
  -webkit-box-orient: horizontal;
  -webkit-box-direction: reverse;
  -ms-flex-direction: row-reverse;
  flex-direction: row-reverse;
}
```

## column-reverse

```css
.flex-direction-row-reverse {
  -webkit-box-orient: vertical;
  -webkit-box-direction: reverse;
  -ms-flex-direction: column-reverse;
  flex-direction: column-reverse;
}
```

## column

```css
.flex-direction-row-reverse {
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
}
```

## 2cols content 

```css
.container {
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.left {
  width: calc(50% - 1rem);
}

.right {
  width: calc(50% - 1rem);
}

@media screen and (max-width: 768px) {
  .container {
    display: block;
  }
  .right, .left {
    width: 100;
  }
}
```

## background image and color
```css
.bg::before {
  content: '';
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  background: #666;
  opacity: 0.5;
  width: 100%;
  height: 100%;
}
```

## fonts
```css
.font-gothic {
  font-family: "Hiragino Sans", "Hiragino Kaku Gothic ProN", "Yu Gothic", "Arial", "Meiryo", sans-serif;
}
.font-mincho {
 font-family: "YuMincho", "Hiragino Mincho ProN", "Yu Mincho", "MS PMincho", serif; 
}
```