# Wedding

## Installation

Install Hugo to start developing

## Deploy to Github Pages

Use deploy.sh to deploy the static site

### Adding content

You can add **a new section to the homepage** via running

```
hugo new homepage/my-new-content.md
```

To create **a page separate from the homepage**, run

```
hugo new my-new-page.md
```

### Using icons

This theme includes the full set of [Font Awesome v4 Icons][font-awesome-icons]. Use the `{{<icon>}}`-[shortcode][hugo-shortcodes] with the respective "fa fa-ICONNAME"-`class` to use an icon directly in your `.markdown` files à la

```markdown
Look at this nice »envelope«-icon: {{<icon class="fa fa-envelope">}}. I took this from https://fontawesome.com/v4.7.0/icon/envelope :-)
```

For the full list of icons, see [Font Awesome v4 Icons][font-awesome-icons].

### Adding your branding / colors / css

Add a `custom_head.html`-file to your `layouts/partials`-directory. In there you may add a `<style>`-tag _or_ you may add a `<link>`-tag referencing your own `custom.css` (in case you prefer to have a separate `.css`-file). Checkout the [`custom_head.html`](https://github.com/janraasch/hugo-scroll/blob/master/exampleSite/layouts/partials/custom_head.html)-file from the `exampleSite`-directory to get started and to find more detailed instructions.

