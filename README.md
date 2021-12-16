# slides

**Amy's AGU slides: <https://nasa-openscapes.github.io/slides/Earthdata_Cloud__Open-Science-Tutorial>**


## Preview slides

Notes from Dec 16: 

In terminal: 

`quarto preview Earthdata_Cloud__Open-Science-Tutorial.ipynb --no-browser`

This will return a url like this: http://localhost:6855/. Use this in combination with your 2i2c url (openscapes.2i2c.cloud/user/jules32/) and "proxy" to view the preview: This example for Julie would be: 

https://openscapes.2i2c.cloud/user/jules32/proxy/6588/

Create your own with:

https://openscapes.2i2c.cloud/user/USERNAME/proxy/LOCALHOST/

Soon, this will auto-refresh but until then, manually refresh your browser tab to see your updates. Your terminal will say "watching for updates".

If you need to stop your terminal, type `Control-C` or close your terminal. Then, you can re-run the command above if need be and update your url to preview slides.

## Making slides

Here is an example: 

- ipynb: <https://github.com/NASA-Openscapes/slides/blob/gh-pages/slides-test.ipynb>
- slides: <https://nasa-openscapes.github.io/slides/slides-test>

To make your `.ipynb` file slides by adding yml specifying the format as "revealjs" in a "raw" cell at the top:

```
---
title: "my title"
format: "revealjs"
---
```