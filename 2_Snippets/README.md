<img alt="Logo" src="http://coderslab.pl/svg/logo-coderslab.svg" width="400">

# Advanced HTML and CSS - Snippets
> Important information


Please read the following guidelines before doing the exercises.

### 1. How to make a simple login form?
Note what fields were used to create it.

```html
<form class="form">
    <fieldset>
        <legend>Log in</legend>

        <input type="email" placeholder="Email">
        <input type="password" placeholder="Password">

        <label for="remember-me">
            <input id="remember-me" type="checkbox"> Remember me
        </label>

        <button type="submit" class="button"></button>
    </fieldset>
</form>
```

### 2. Centering an element vertically and horizontally within another element

```html
<div class="one">
    <div class="two">
    </div>
</div>
```

```css
.one {
    display: flex;
    justify-content: center;
    align-items: center;
}

.two {
    width: 50px;
    height: 50px;
    background-color: red;
}
```
More information [under this link](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).
