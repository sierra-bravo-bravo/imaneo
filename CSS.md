# Nomenclature CSS

Le site utilise des utilitaires Tailwind (`flex`, `col-span-12`, `p-5`…) et un petit jeu de classes maison, nommées ainsi :

- **Composants** en kebab-case, éléments en `__` : `site-nav`, `nav-link`, `nav-menu-link`, `nav-mobile`, `nav-mobile__toggle`, `building-card`, `building-card__shape`, `building-list`, `building-list__arrow`, `video-frame`, `btn-reset`, `page`.
- **États** préfixés `is-` (posés par le JS) : `is-loading`, `is-visible`, `is-leaving`, `is-nav-hidden`.
- **Effets d'animation** préfixés `fx-` (cibles GSAP/Splitting, sans style propre) : `fx-reveal`, `fx-split` (+ attributs `data-splitting`, `data-effect16`…).

| Avant | Après |
|---|---|
| `navbar-bg` | `site-nav` |
| `navlink` | `nav-link` |
| `menu-link` | `nav-menu-link` |
| `mobile-menu` / `mobile-menu-button` | `nav-mobile` / `nav-mobile__toggle` |
| `unbutton` | `btn-reset` |
| `transition-container` | `page` |
| `loading` / `fade-in` / `fade-out` / `fade-out-on-scroll` | `is-loading` / `is-visible` / `is-leaving` / `is-nav-hidden` |
| `text-fade` / `content__title` | `fx-reveal` / `fx-split` |
| `card-bat` / `shape` | `building-card` / `building-card__shape` |
| `bat-list` / `arrow` | `building-list` / `building-list__arrow` |
| `video` | `video-frame` |

Classes supprimées car sans effet (ni CSS ni JS) : `lol`, `oh`, `item-img`, `container_big_img`, `btn_scroll`, `demo-2`.
