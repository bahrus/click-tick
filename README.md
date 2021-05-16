# click-tick [TODO]

MS Powerpoint provides a nice feature, where you can create a slide with bullet points, and as you click the mouse, the bullet points appear (with optional animation effects).  This allows the presenter to easily walk through a list of items, without overwhelming the user with information overload when the slide appears.

This web component affects target elements.

Say you have a list:

```html
<ul>
    <li>
        Phase I -- Collect Underpands
    </li>
    <li>
        Phase II -- ?
    </li>
    <li>
        Phase III -- Profit
    </li>
</ul>
```

We want to specify that as we click anywhere within the list, we set some specified attribute or class to the sequence of li's.