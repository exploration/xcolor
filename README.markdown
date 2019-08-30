# XCOLOR
This is designed to be used with [pastel](https://github.com/sharkdp/pastel), to facilitate color lookup for EXPLO-specific colors.

It will scrape the hex code for a passed color name from our [Style Guide](https://styleguide.lab.explo.org), and return it. It also keeps a local cache of colors that have already been looked up so that it doens't have to hit the web site each time.

## USAGE

```bash
> xcolor orange
#F79421

pastel color $(xcolor orange)

  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀  Hex: #f79421
  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀  RGB: rgb(247, 148, 33)
  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀  HSL: hsl(32, 93.0%, 54.9%)
  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀  Most similar:
  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀   ▀▀▀▀▀ darkorange
  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀   ▀▀▀▀▀ orange
  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀   ▀▀▀▀▀ sandybrown
  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
```