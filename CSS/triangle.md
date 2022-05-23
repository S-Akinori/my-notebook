# triangle with linear-gradient

```css
.bottom{
    background:
      linear-gradient(to top right, rgba(255,255,255,0) 50%, #f00 50.5%) no-repeat top left/50% 100%,
      linear-gradient(to top left, rgba(255,255,255,0) 50%, #f00 50.5%) no-repeat top right/50% 100%;
}
.top{
    background:
      linear-gradient(to bottom right, rgba(255,255,255,0) 50%, #f00 50.5%) no-repeat top left/50% 100%,
      linear-gradient(to bottom left, rgba(255,255,255,0) 50%, #f00 50.5%) no-repeat top right/50% 100%;
}
.left{
    background:
      linear-gradient(to top right, rgba(255,255,255,0) 50%, #f00 50.5%) no-repeat bottom left/100% 50%,
      linear-gradient(to bottom right, rgba(255,255,255,0) 50%, #f00 50.5%) no-repeat top right/100% 50%;
}
.right{
    background:
      linear-gradient(to bottom left, rgba(255,255,255,0) 50%, #f00 50.5%) no-repeat top left/100% 50%,
      linear-gradient(to top left, rgba(255,255,255,0) 50%, #f00 50.5%) no-repeat bottom right/100% 50%;
}
.topRight{
    background:
      linear-gradient(to top right, rgba(255,255,255,0) 50%, #f00 50.5%) no-repeat top left/100% 100%;
}
.topLeft{
    background:
      linear-gradient(to top left, rgba(255,255,255,0) 50%, #f00 50.5%) no-repeat top left/100% 100%;
}
.bottomRight{
    background:
      linear-gradient(to bottom right, rgba(255,255,255,0) 50%, #f00 50.5%) no-repeat top left/100% 100%;
}
.bottomLeft{
    background:
      linear-gradient(to bottom left, rgba(255,255,255,0) 50%, #f00 50.5%) no-repeat top left/100% 100%;
}
```