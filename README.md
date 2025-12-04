# Lost in Tra(i)nslation - Ontwerpdocumentatie

## Over het project

**Lost in Tra(i)nslation** is een webgebaseerd ontwerp- en prototypingproject gemaakt door Diana Biygereyeva (1GDM2). Het project documenteert de ontwikkeling van interactieve en niet-interactieve schermen voor een digitale ervaring, met gebruik van HTML, CSS en Figma.

Het doel van dit project is om een overzichtelijke en gestructureerde prototypeomgeving te creëren waarin zowel mobiele als desktopervaringen worden getest en gedocumenteerd.

---

## Structuur van het project

Het project is opgebouwd uit de volgende onderdelen:

### Bestanden en mappen

- **index.html** – Hoofdpagina van de ontwerpdocumentatie.
- **assets/** – Map met alle CSS-bestanden en andere stijlelementen:
  - `styles.css` – Algemene styling.
  - `flexboxes.css` – Flexbox layouts.
  - `nav.css` – Navigatiebalk styling.
  - `typography.css` – Typografie regels.
- **dist/output.css** – Gecompileerde Tailwind CSS output.
- **public/assets/schermen/** – HTML-bestanden van individuele schermen:
  - `overzichtscherm.html`
  - `perronscherm.html`
  - `wagonindelingsscherm.html`

---

## Functionaliteiten

- **Responsieve navigatiebalk**

  - Mobiel menu met slide-down animatie.
  - Desktop menu met actieve link highlight.
  - Auto-hide navbar bij scrollen.

- **Accordeoncomponent**

  - Klikbare secties om schermoverzichten te tonen.
  - Ondersteuning voor interactieve en niet-interactieve prototypes.

- **Prototypes**
  - Niet-interactieve schermen: HTML-bestanden in `public/assets/schermen/`.
  - Interactieve schermen: Figma mobiele prototypes [hier beschikbaar](https://www.figma.com/design/2jDPdwS682WixnVWT0lYmH/2526_PRTT_BiygereyevaDiana_Midi-prototypes-v?node-id=164-533&t=O2xaZ30KgK7UUeG0-1).

---

## Technologieën

- HTML
- CSS + TailwindCSS
- Google Fonts: **Roboto** en **Montserrat**
- JavaScript (voor navigatie en accordeon interacties)
- Figma (voor interactieve prototypes)

---

## Styling en typografie

- Fonts geïmporteerd via Google Fonts:
  ```css
  @import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap");
  @import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap");
  ```
