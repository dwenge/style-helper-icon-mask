# Style helper icon mask

Добавление иконок

```css
.i_lg {
  --dw-icon-width: 2rem;
}
.i-example {
  --dw-icon: url("https://unpkg.com/bootstrap-icons@1.13.1/icons/bootstrap-fill.svg");
}
```

Использование

```html
<p style="color: white; background-color: black">
  <span class="i i_mask i-example i_lg"></span>
  Mask (change color)
</p>
```
