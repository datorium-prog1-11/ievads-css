# CSS

- Cascading style sheents
- Noformatē HTML dokumentu
- Izskats, izkārtojums

---

## Pielietojams uz izvēlētajiem HTML elementiem

- atribūts uz konkrēta elementa: `style=""`
- elementa selektors: `p`
- klases selektors: `.paragrafs`
- vairāku klašu selektors: `.paragrafs.cita-klase`
- id selektors (priekš JavaScript): `#spec-paragrafs`

---

## Stila atribūts:

HTML + CSS

```html
<p style="color: blue; font-size: 20px">Teksta fragments</p>
```

---

## Elementa selektors:

### HTML

```html
<p>Teksta fragments</p>
```

### CSS

```css
p {
    font-size: 17px;
}
```

---

## Klases atribūts un selektors:

### HTML

Priekš klases selektora.

```html
<p class="paragrafs">Teksta fragments</p>
<p class="paragrafs cita-klase">Teksta fragments</p>
```

### CSS

Noformē visus elementus, kam `class` atribūts satur doto klasi.

```css
.paragrafs {
    color: blue;
    font-weight: light;
}
```

Noformē visus elementus, kam `class` atribūts satur abas dotās klases.

```css
.paragrafs.cita-klase {
    font-weight: bold;
}
```

---

## Id atribūts:

### HTML

Priekš `id` selektora. Pārsvarā priekš JavaScript.

```html
<p id="spec-paragrafs">Teksta fragments</p>
```

### CSS

Noformē elementu ar doto `id` atribūta vērtību. Šo parasti CSS neizmanto.

```css
#spec-paragrafs {
    backtround-color: red;
}
```

---


## Populāri CSS parametri (properties):

- `display` - kā elements tiek attēlots lapā un vai vispār tas tiek attēlots
- `width` / `height` - platums, augstums
- `margin` / `padding` - atkāpes no elementa malām, ārpusē un iekšpusē
- `border` - līnija apkārt elementam
- `float` - elementa novietojums attiecībā pret tekstu
- `color` - teksta krāsa
- `background` / `background-color` - elementa fons
- `font-...`(`size`, `weight`, `family`) - fonta noformējums
- `line-height` - teksta rindas augstums
- `text-decoration` - teksta noformējums (apakšvītra, nosvītrojums)
- `position` - pozīcijas veids

---

## Tālāka lasīšana par CSS (Angliski):

- https://zellwk.com/blog/9-important-css-properties-you-must-know/
- Flex box zombies: https://geddski.teachable.com/p/flexbox-zombies
