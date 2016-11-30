# Erudus Allergen & Dietary Icon Font

The `dist` folder contains all files need to use the icons in a project. See index.html for example useage.

## Using with SASS

import `_icons.scss` from the `dist/sass` folder.

## Example 1

Drop a simple icon into your project:

`<span class="eicon eicon-circle-cereal"></span>`

## Example 2

Requires the sass version. Produce a list of icons with colour coded levels:

```
<ul class="eicon-list">
        <li class="allergen-level-yes"><span class=" eicon eicon-circle-cereal"></span>Cereal</li>
        <li class="allergen-level-may"><span class=" eicon eicon-circle-gluten"></span>Gluten</li>
        <li><span class=" eicon eicon-circle-milk"></span>Milk</li>
</ul>
```
