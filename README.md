# Mappa Semantica — Clone PlayStation (`index.html`)

---

## Albero della struttura HTML

- `html`
  - `head`
    - `meta[charset="UTF-8"]`
    - `meta[http-equiv="X-UA-Compatible"][content="IE=edge"]`
    - `meta[name="viewport"][content="width=device-width, initial-scale=1.0"]`
    - `link` → Bootstrap 5.3.8 CSS (CDN)
    - `link` → Bootstrap Icons 1.13.1 (CDN)
    - `link` → css/style.css
  - `body`
    - `header.header.fixed-top`
      - `div.header-top.text-end.pe-3.pt-1.pb-1`
        - `img.header-top-logo` — logo Sony
      - `div.header-bottom.bg-white`
        - `nav.navbar.navbar-light.navbar-expand-lg`
          - `div.container-fluid`
            - `a.navbar-brand` — logo PlayStation
            - `button.navbar-toggler` [data-bs-toggle="collapse"] — hamburger ☰
            - `div#navbarSupportedContent.collapse.navbar-collapse.justify-content-between`
              - `ul.navbar-nav.mb-2.mb-lg-0` — menu sinistra (6 voci)
                - (×6) `li.nav-item.dropdown.position-static`
                  - `a.nav-link.dropdown-toggle` [data-bs-toggle="dropdown"]
                  - `ul.dropdown-menu.border-0.rounded-0.w-100.list-inline.text-center`
                    - (×3) `li.list-inline-item` → `a.dropdown-item` — item con immagine
                    - `hr.dropdown-divider`
                    - `li` → `ul.sub-dropdown.d-flex.justify-content-center.p-0`
                      - (×3) `li.ms-3.me-3` → `a` — link testuali
              - `ul.navbar-nav.mb-2.mb-lg-0.align-items-center` — menu destra
                - `li.nav-item.dropdown.position-static` — "My PlayStation"
                - `li.nav-item` → `a.btn.btn-dark.btn-inset.rounded-pill` — "Accedi"
                - `li` → `a` → `img.w-50.ms-2` — icona cerca
    - `main`
      - `section.jumbotron.mb-5`
        - `div.container` → `div.row` → `div.col-5`
          - `img` — logo gioco
          - `h2` — titolo
          - `p` — descrizione
          - `a.btn.btn-danger` — "Acquista ora"
      - `section.thumbs`
        - `div.container`
          - `div.row.row-cols-2.row-cols-sm-3.row-cols-lg-6.align-items-center`
            - (×6) `div.mb-3.mb-lg-0` → `a` [primo: a.active] → `img.rounded-6.img-fluid`
      - `section.playstation-info.mt-5.text-center`
        - `h4.title-4` — "Play Has No Limits"
        - `h2.title-2.mb-4` — "Ecco la PlayStation 5"
        - `h3.title-3` — sottotitolo
      - `section.playstation-display`
        - `div.container` → `div.row.align-items-center`
          - `div.col-12.col-md-5` — testo + a.btn.btn-primary
          - `div.col-12.col-md-7.text-center` — img console PS5
          - `div.playstation-thumbs.row.row-cols-3.row-cols-md-5.align-items-stretch.mb-5`
            - (×5) `div.col.mb-3.mb-md-0` → `a.d-block.h-100.text-center`
              - `img.w-50.ms-auto.me-auto.mb-5`
              - `span.d-none.d-md-block` — nome accessorio
      - `section.banner-game`
        - `div.container.pt-5.pb-5` → `div.row` → `div.col-lg-6.col-xl-4`
          - `img.logo` — logo "It Takes Two"
          - `h2` — titolo gioco
          - `p` — descrizione
          - `a.btn.btn-danger.btn-inset.rounded-pill` — "Acquista ora"
      - `section.game-grid.pt-5`
        - `div.container`
          - `div.row.mb-3` — h2 + h3 intestazione sezione
          - `div.row.row-cols-2.row-cols-sm-3.row-cols-lg-6`
            - (×12) `div.col.mb-5` → `a`
              - `img.img-fluid.rounded-6.mb-4`
              - `span` — titolo gioco
      - `section.play4.pt-5.pb-5`
        - `div.container`
          - `section.play4-intro.mb-5.text-center`
            - `h2.title-2.mb-4`
            - `h3.title-3`
          - `section.display`
            - `div.row.row-cols-1.row-cols-md-3`
              - (×3) `div.col.mb-5.mb-md-0` → `a.text-center`
      - `section.banner-plus.bg-grey`
        - `div.container` → `div.row.align-items-center`
          - `div.col-12.mt-5.mb-5.col-md-6.mt-md-0.mb-md-0` — logo PS+, p, btn
          - `div.d-none.d-md-block.col-md-6` — immagine decorativa
      - `section.discount`
        - `section.container.mt-5.mb-5.text-center` — h2 + h3
        - `section.container`
          - `div.row.row-cols-1.row-cols-md-3`
            - (×3) `div.col.mb-5` — img promo
      - `section.banner-plus.bg-blue-dark.text-white`
        - `div.container` → `div.row.align-items-center`
          - `div.col-12.mt-5.mb-5.col-md-6.mt-md-0.mb-md-0` — logo PS Now, p, btn
          - `div.d-none.d-md-block.col-md-6` — immagine decorativa
    - `footer`
      - `section.footer-social`
        - `section.container.mt-5.mb-5.text-center` — h2
        - `div.container` → `div.row` → `div.col-sm-6.offset-sm-3`
          - `div.row.row-cols-2.row-cols-sm-4`
            - (×4) `div.col.mb-5` → `a.text-center` → `img.img-fluid`
      - `section.footer-menu.bg-blue.text-white.pt-5.pb-5`
        - `div.container`
          - `div.row.mb-5`
            - `div.col-lg-6.mb-5.mb-lg-0` — img logo PS + a[selettore regione]
            - (×3) `div.col-md-4.col-lg-2` → `ul.list-unstyled` → `li` → `a`
          - `div.row.mt-5.mt-lg-0`
            - `div.col-lg-6` — img.logo-sony + p[copyright]

---

## Componenti Bootstrap utilizzati

| Componente | Classe/i principali | Dove viene usato |
|---|---|---|
| **Navbar** | `.navbar` `.navbar-expand-lg` `.navbar-collapse` | `header-bottom` |
| **Dropdown** | `.dropdown` `.dropdown-menu` `.dropdown-item` | Ogni voce nav + "My PlayStation" |
| **Grid — Container** | `.container` `.container-fluid` | Tutte le sezioni (`.container-fluid` solo nella navbar) |
| **Grid — Row** | `.row` | Tutte le sezioni |
| **Grid — Col** | `.col-*` `.col-md-*` `.col-lg-*` `.col-xl-*` | Tutte le sezioni |
| **Responsive cols** | `.row-cols-*` `.row-cols-sm-*` `.row-cols-lg-*` | `.thumbs`, `.game-grid`, `.play4`, `.footer-social` |
| **Buttons** | `.btn` `.btn-danger` `.btn-primary` `.btn-dark` `.btn-light` | CTA in ogni sezione |
| **Spacing** | `.mt-*` `.mb-*` `.ms-*` `.me-*` `.pt-*` `.pb-*` `.pe-*` | Spaziature ovunque |
| **Display** | `.d-none` `.d-md-block` `.d-flex` `.d-block` | Visibilità responsive |
| **Text** | `.text-center` `.text-white` `.text-end` | Allineamento testi |
| **Flex align** | `.align-items-center` `.justify-content-center` `.justify-content-between` | Allineamento flex |
| **List inline** | `.list-inline` `.list-inline-item` | Dropdown con immagini |
| **List unstyled** | `.list-unstyled` | Liste nel footer |
| **Images** | `.img-fluid` | Tutte le immagini responsive |
| **Offset** | `.offset-sm-3` | Footer social (centra la colonna delle icone) |
| **Border utils** | `.border-0` `.rounded-0` `.rounded-6` `.rounded-pill` | Dropdown, immagini, bottoni |
| **Background** | `.bg-white` `.bg-grey` `.bg-blue` `.bg-blue-dark` | Header, banner, footer |

---

## Glossario

### Bootstrap Grid

| Termine | Significato |
|---|---|
| **Container** | `div.container` — box centrato con larghezza massima e padding laterale. `.container-fluid` occupa tutta la larghezza |
| **Row** | `div.row` — riga flex che contiene colonne. Annulla il padding del container con margini negativi |
| **Col** | `div.col-*` — colonna della griglia (12 colonne totali). `col-md-6` = metà larghezza da breakpoint `md` in su |
| **Row-cols** | `div.row-cols-*` — definisce quante colonne per riga, senza dichiarare la larghezza su ogni singola colonna. Es: `row-cols-lg-6` = 6 colonne per riga da `lg` in su |
| **Breakpoint** | Soglia di larghezza schermo: `sm` ≥576px, `md` ≥768px, `lg` ≥992px, `xl` ≥1200px |
| **Offset** | `offset-sm-3` — sposta la colonna a destra di 3 unità di griglia, effettivamente centrandola quando combinata con `col-sm-6` |

### Navbar e Dropdown

| Termine | Significato |
|---|---|
| **`navbar-expand-lg`** | La navbar mostra le voci in orizzontale da `lg` in su; sotto `lg` collassa nell'hamburger |
| **`navbar-toggler`** | Bottone hamburger (☰) visibile solo sotto `lg`; controlla il collapse |
| **`collapse.navbar-collapse`** | Contenitore delle voci di menu: visibile da `lg`, nascosto (collassato) sotto `lg` |
| **`justify-content-between`** | Distribuisce i due `ul.navbar-nav` agli estremi del collapse (menu sx e menu dx) |
| **`dropdown-toggle`** | Elemento che apre/chiude il dropdown al click; richiede `data-bs-toggle="dropdown"` |
| **`sub-dropdown`** | Classe custom del progetto: secondo livello del menu a tendina, con link testuali in riga flex |

### Responsive e Utilities

| Termine | Significato |
|---|---|
| **`d-none d-md-block`** | Nasconde l'elemento per default, lo mostra come `block` da `md` in su — pattern comune per elementi decorativi |
| **`img-fluid`** | `max-width: 100%; height: auto` — l'immagine non supera la larghezza del suo contenitore |
| **`rounded-6`** | Classe Bootstrap 5.3 con `border-radius` predefinito (livello 6) — arrotonda gli angoli delle card giochi |
| **`btn-inset`** | Classe custom del progetto (non Bootstrap) — probabilmente aggiunge una variazione visiva al bottone |
| **`bg-grey` / `bg-blue` / `bg-blue-dark`** | Classi custom del progetto per sfondi non presenti nelle utility Bootstrap standard |
