# Typos

> Typo definitions and generating style blocks for each viewport

## Definition

Here are all [definition](definition/definition.scss):

| Name | Description |
| ------------- |-------------|
| body | Default [document body](../../base/documents/css/document.scss) styles |
| button | Button text |
| footer | Footer text |
| popup-text | Popup clickable link text |
| popup-title | Popup title |
| quote | Quote text name |
| text | Default text |
| title | Headings |

## Usage

Use the `font()` [mixin](css/typos.scss) with a name to get all styles for this definition for each viewport e.g. for title:

```html
h1 {
    @include font('title');
}
```
