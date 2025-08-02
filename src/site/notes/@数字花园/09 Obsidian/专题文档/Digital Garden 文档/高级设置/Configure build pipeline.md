---
{"dg-publish":true,"dg-path":"09 Obsidian/专题文档/Digital Garden 文档/高级设置/Configure build pipeline.md","permalink":"/09 Obsidian/专题文档/Digital Garden 文档/高级设置/Configure build pipeline/","noteIcon":"dg-note-icon","created":"2023-03-09T14:58:29.563+01:00","updated":"2023-03-09T15:03:54.208+01:00"}
---


The digital garden uses 11ty when building the site, and markdown-it for rendering markdown to html. 
If you want to configure either the 11ty build pipeline or the markdown rendering engine you can do so in the `src/helpers/userSetup.js` file. There should be two functions there: `useMarkdownSetup(md)` and `userEleventySetup(eleventyConfig)`. These will be called after all the default setup has been processed, and allows you to do modifications on both the eleventy config and the markdown-it instance. For examples on how these are configured, you can have a look in the `.eleventy.js` file in the root directory of your site.  