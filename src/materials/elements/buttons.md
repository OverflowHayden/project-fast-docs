---
name: Buttons
category: Elements
---

```buttons.html
<button class="button">Button</button>
<button class="button button--alt">Button alt</button>
<button class="button button--text">Text</button>
```

### Icon buttons
```iconbuttons.html
<button class="button"><span class="iconify" data-icon="mdi:cloud-download"></span>Button</button>
<button class="button button--alt"><span class="iconify" data-icon="mdi:cloud-download"></span>Button alt</button>
<button class="button button--text"><span class="iconify" data-icon="mdi:cloud-download"></span>Text</button>
```

### Compact buttons
```compact.html
<button class="button button--compact"><span class="iconify" data-icon="mdi:cloud-download"></span>Button</button>
<button class="button button--compact button--alt">Button alt</button>
<button class="button button--compact button--text">Text</button>
```

### Icon
```icon.html
<button class="button button--icon"><span class="iconify" data-icon="mdi:eye"></span></button>
<button class="button button--icon button--alt"><span class="iconify" data-icon="mdi:pencil"></span></button>
<button class="button button--icon button--text"><span class="iconify" data-icon="mdi:delete"></span></button>
```

#### Variables
```
@use "setup/variables" with (
    $button: (
        "background": red,
        "border-radius": .1875em,
        "color": white,
        "font-size": 1.6rem,
        "padding": .75em 1.375em .6875em,
        "compact": (
            "font-size": 80%,
            "padding": .5em 1em .4375em,
        )
    )
);
```