---
title: "Cryptolive"
date: 2018-06-03T20:06:40-07:00
draft: false
---

Added in `v0.0.5`.

Compare crypto currencies using [CryptoCompare](https://cryptocompare.com).

## Source Code

```bash
wtf/cryptocurrencies/cryptolive/
```

## Required ENV Vars

None.

## Keyboard Commands

None.

## Configuration

```yaml
cryptolive:
  colors:
    from:
      name: coral
      displayName: grey
    to:
      name: white
      price: green
  currencies:
    BTC:
      displayName: Bitcoin
      to:
        - USD
        - EUR
        - ETH
    ETH:
      displayName: Ethereum
      to:
        - USD
        - EUR
        - ETH
  enabled: true
  position:
    top: 5
    left: 2
    height: 1
    width: 2
  refreshInterval: 30
  updateInterval: 15
```

### Attributes

`colors.from.name` <br />
Values: Any <a href="https://en.wikipedia.org/wiki/X11_color_names">X11
color name</a>.

`colors.from.dispayName` <br />
Values: Any <a href="https://en.wikipedia.org/wiki/X11_color_names">X11
color name</a>.

`colors.to.name` <br />
Values: Any <a href="https://en.wikipedia.org/wiki/X11_color_names">X11
color name</a>.

`colors.to.price` <br />
Values: Any <a href="https://en.wikipedia.org/wiki/X11_color_names">X11
color name</a>.

`currencies` <br />

`enabled` <br />
Determines whether or not this module is executed and if its data displayed onscreen. <br />
Values: `true`, `false`.

`position` <br />
Defines where in the grid this module's widget will be displayed. <br />

`refreshInterval` <br />
How often, in seconds, this module will update its data. <br />
Values: A positive integer, `0..n`.
