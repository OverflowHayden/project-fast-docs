---
name: Cards
category: Components
---

Add a [grid column](#grid) class like `.col__sm--6` to the card to change size. Image is optional.
```card.html
<div class="card">
    <figure class="card__image"><img src="https://placebeard.it/460/320" alt="Placebeard" /></figure>
    <div class="card__content">
        <h2 class="card__title">Card title</h2>
        <p>Aenean pellentesque vel odio sed tincidunt. Curabitur rutrum commodo hendrerit. Vestibulum iaculis turpis at odio sagittis fringilla.</p>
        <div class="card__actions">
            <a href="#" class="button button--compact">Save</a>
            <a href="#" class="button button--compact button--text">Cancel</a>
        </div>
    </div>
</div>

<div class="card">
    <div class="card__content">
        <h2 class="card__title">Card title</h2>
        <h3 class="card__subtitle">Card subtitle</h3>
        <p>Aenean pellentesque vel odio sed tincidunt. Curabitur rutrum commodo hendrerit. Vestibulum iaculis turpis at odio sagittis fringilla.</p>
        <div class="card__actions">
            <div class="card__buttons">
                <a href="#" class="button">Save</a>
                <a href="#" class="button button--text">Cancel</a>
            </div>
            <div class="card__icons">
                <a href="#" class="button button--icon button--text"><span class="iconify" data-icon="mdi:share"></span></a>
                <a href="#" class="button button--icon button--text"><span class="iconify" data-icon="mdi:dots-vertical"></span></a>
            </div>
        </div>
    </div>
</div>
```

#### Variables
```
@use "~project-fast/src/scss/components/card" with (
    $card: (
        "background": variables.$color-base-white,
        "color": rgba(variables.$color-base-black,.54),
        "font-size": 1.4rem,
        "padding": 1.6rem,
        "title": (
            "color": variables.$color-base-black,
            "font-size": 2rem,
        ),
        "subtitle": (
            "color": rgba(variables.$color-base-black, .65),
            "font-size": 1.4rem,
        ),
        "button": (
            "color": rgba(variables.$color-base-black, .65),
            "font-size": 1.8rem,
        ),
    ),
);
```