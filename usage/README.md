# Picture

This component is based on the blueprint of Veams-Components.

## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: quote, @tag: component-partial }}
{{#with picture-bp}}
	{{> c-picture}}
{{/with}}
{{! @INSERT :: END }}
```

### Include: SCSS

``` scss
// @INSERT :: START @id: scss-import
@import "components/_c-picture";
// @INSERT :: END
```