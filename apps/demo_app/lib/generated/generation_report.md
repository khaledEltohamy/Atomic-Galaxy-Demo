# Galaxy generation report

How each of the 163 generated layers was understood.

## Decided by

| Source | Layers | Share |
|---|---:|---:|
| name | 125 | 76.7% |
| default | 38 | 23.3% |

`default` means "drawn exactly as in Figma, no behaviour". That is correct for plain layout frames.

## Widgets produced

| Kind | Count |
|---|---:|
| text | 43 |
| container | 38 |
| button | 16 |
| spacer | 10 |
| icon | 9 |
| divider | 6 |
| appBar | 6 |
| radio | 5 |
| image | 4 |
| textField | 4 |
| card | 4 |
| navigationBar | 3 |
| dropdown | 3 |
| switchControl | 3 |
| checkbox | 2 |
| listView | 2 |
| grid | 2 |
| pageView | 1 |
| pageIndicator | 1 |
| slider | 1 |

## Needs a human look (6)

These look interactive but were not recognised. Name the layer (for example `button`), bind its fill to a `button*` variable, or add a rule to `galaxy_rules.json`.

- `ProductDetails` / `badge` (50:95): looks like a button / chip, kept as a plain box
- `ProductDetails` / `tab` (I50:102;44:85): looks like a button / chip, kept as a plain box
- `ProductDetails` / `tab` (I50:102;44:87): looks like a button / chip, kept as a plain box
- `Cart` / `cart-item` (50:166): looks like a button / chip, kept as a plain box
- `Cart` / `cart-item` (50:177): looks like a button / chip, kept as a plain box
- `OrderPlaced` / `status` (58:192): looks like a button / chip, kept as a plain box

## Icons without an SVG (0)

Nothing.
