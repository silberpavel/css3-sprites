# css3-sprites

```
ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

.buttons li {
    background: url(css-sprite2.gif);
    display: inline-block;
    width: 128px;
    height: 32px;
    cursor: pointer;
}

.buttons .button1:hover {
    background-position: 0 -32px;
}

.buttons .button1:active {
    background-position: 0 -64px;
}
```

```
    <ul class="buttons">
        <li class="button1"></li>
        <li class="button2"></li>
        <li class="button3"></li>
    </ul>
```