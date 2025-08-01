---
{"dg-publish":true,"dg-path":"09 Obsidian/专题文档/Digital Garden 文档/高级设置/CSS Customization.md","permalink":"/09 Obsidian/专题文档/Digital Garden 文档/高级设置/CSS Customization/","created":"2023-02-17T17:01:23.938+01:00","updated":"2023-02-17T17:16:56.750+01:00"}
---


## Dynamic CSS/SCSS

Any css/scss files placed under `src/site/styles/user` will automatically be linked into the head right after all other styling. Meaning that the styling added here will take presedence over everything else. 

## Available css variables
Not all themes looks good out of the box. The template makes some css variables available to customize various css properties to customize it to your need.
Currently the available css variables are
`--graph-main`
`--graph-muted`


> [!note] The !important attribute
> Some styles uses the `!important` attribute. This is by most considered bad practice, but it is unfortunately neccessary in some places to override styling coming from whatever theme you've chosen. If your changes css changes doesn't reflect on your site, try adding an `!important` behind it and see if that helps. 


> [!warning] Deprecated
> Previously the only way to add custom styling to the site was to add styling to the `custom-styles.scss` file. This is still possible to do, but is considered deprecated.