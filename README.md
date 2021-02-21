# CSS

- Cascading style sheents
- Noformatē HTML dokumentu
- Izskats, izkārtojums

## Applicable to select elements

- `style=""`
- element `p`
- class `.paragraph`
- class `.paragraph.cita-klase`
- id `#this-special-paragraph`

## HTML

```html
<p id="this-special-paragraph" class="paragraph cita-klase"></p>
```

## CSS

```CSS
p {
    font-size: 17px;
}
.paragraph {
    font-size: 18px;
}

.paragraph {
    color: blue;
    font-weight: bold;
}

#this-special-paragraph {
    backtround-color: red;
}
```

### Properties:

- display
- width / height
- margin / padding
- border
- float
- color
- background / background-color
- font (size, weight, family)
- line-height
- text-decoration
- position

## Example:

- https://zellwk.com/blog/9-important-css-properties-you-must-know/
- Flex box zombies: https://geddski.teachable.com/p/flexbox-zombies
