# CSS Checklist for Assignment 2

Student: Aiserik Yerbol

## Stylesheet files

- Shared stylesheet: `css/base.css`
- Personal stylesheet: `css/aiserik.css`
- Load order: every HTML page links `base.css` first and `aiserik.css` second.

## Selectors

| Requirement | File | Line | Example |
|---|---:|---:|---|
| Universal selector | `css/base.css` | 10 | `*` |
| Type selector | `css/base.css` | 20 | `body` |
| Class selector | `css/base.css` | 88 | `.site-header` |
| ID selector | `css/base.css` | 210 | `#contact` |
| Descendant selector | `css/base.css` | 138 | `.site-nav a` |
| Child selector | `css/base.css` | 127 | `.site-nav > ul` |
| Adjacent sibling selector | `css/base.css` | 42 | `h2 + p` |
| Grouping selector | `css/base.css` | 28 | `h1, h2, h3` |
| Attribute selector | `css/aiserik.css` | 172 | `a[href^="mailto:"]::after` |
| `:hover` pseudo-class | `css/base.css` | 51 | `a:hover` |
| `:focus` pseudo-class | `css/base.css` | 52 | `a:focus` |
| `:nth-child` pseudo-class | `css/aiserik.css` | 52 | `.menu-table tbody tr:nth-child(even)` |
| `::before` pseudo-element | `css/base.css` | 108 | `.site-title::before` |
| `::after` pseudo-element | `css/aiserik.css` | 172 | `a[href^="mailto:"]::after` |

## Classes and IDs

- Reused classes include `.site-header`, `.site-nav`, `.page-shell`, `.page-section`, `.media-card`, `.site-footer`, `.contact-block`, `.fixed-call`, `.skip-link`.
- IDs include `#main-content`, `#about`, `#contact`, `#prices`, `#categories`, and `#order-form`.
- HTML comments explain why key IDs are unique where they are used.

## Colors, Fonts, Spacing, and Alignment

| Requirement | File | Line | Example |
|---|---:|---:|---|
| Palette comment | `css/base.css` | 1 | Five-color palette and reasons |
| Hex colors | `css/base.css` | 22 | `#f7ead2` |
| RGB color | `css/base.css` | 23 | `rgb(31, 25, 19)` |
| RGBA color | `css/base.css` | 5 | `rgba(23, 64, 42, 0.12)` |
| Named color | `css/base.css` | 66 | `white` |
| First font stack | `css/base.css` | 14 | `Georgia, "Times New Roman", serif` |
| Second font stack | `css/base.css` | 31 | `"Trebuchet MS", Verdana, Arial, sans-serif` |
| Box sizing | `css/base.css` | 11 | `box-sizing: border-box` |
| Margin auto centering | `css/base.css` | 154 | `margin: 0 auto` |
| Padding | `css/base.css` | 78 | `padding` |
| Border | `css/base.css` | 80 | `border` |
| Text alignment | `css/base.css` | 85 | `text-align: center` |
| Margin collapse comment | `css/base.css` | 219 | section padding prevents heading margin collapse |

## Cascade and Priority

| Requirement | File | Line | Example |
|---|---:|---:|---|
| Internal style block | `index.html` | 12 | `.cascade-demo` override |
| Inline style attribute | `order.html` | 120 | `.promo-code` letter spacing |
| Specificity lower rule | `css/aiserik.css` | 139 | `.form-card` |
| Specificity higher rule | `css/aiserik.css` | 144 | `#order-form.form-card` |
| `!important` | none | none | Not used |

## Flexbox

| Requirement | File | Line | Example |
|---|---:|---:|---|
| Navigation flex row | `css/base.css` | 127 | `.site-nav > ul` |
| `justify-content` | `css/base.css` | 131 | `justify-content: center` |
| `align-items` | `css/base.css` | 132 | `align-items: center` |
| `gap` | `css/base.css` | 133 | `gap: 1rem` |
| `flex-direction` | `css/base.css` | 129 | `flex-direction: row` |
| `flex-wrap` | `css/base.css` | 226 | footer wrapping |
| Growing and shrinking items | `css/base.css` | 236 | `flex: 1 1 18rem` |
| Page-specific flex block | `css/aiserik.css` | 61 | `.category-panel ol` |

## Grid

| Requirement | File | Line | Example |
|---|---:|---:|---|
| Page grid | `css/base.css` | 160 | `.page-shell` |
| Section grid | `css/base.css` | 169 | `.page-section` |
| `repeat()` | `css/base.css` | 169 | `repeat(2, minmax(0, 1fr))` |
| `fr` units | `css/base.css` | 169 | `1fr` |
| `minmax()` | `css/base.css` | 169 | `minmax(0, 1fr)` |
| `gap` | `css/base.css` | 170 | `gap: 0.75rem 1rem` |
| Spanning item | `css/base.css` | 181 | `grid-column: 1 / -1` |
| Grid explanation comment | `css/base.css` | 166 | why grid suits content sections |

## Positioning, Float, Clear, and Centering

| Requirement | File | Line | Example |
|---|---:|---:|---|
| `position: static` | `css/base.css` | 167 | `.page-section` |
| Static explanation comment | `css/base.css` | 165 | normal document flow |
| `position: relative` | `css/base.css` | 89 | `.site-header` |
| Relative explanation comment | `css/base.css` | 87 | containing block |
| `position: absolute` | `css/base.css` | 115 | `.site-tagline` |
| `position: fixed` | `css/base.css` | 75 | `.fixed-call` |
| Float image | `css/aiserik.css` | 12 | `.story-photo` |
| Clear float | `css/aiserik.css` | 19 | `.clear-float` |
| Clear explanation comment | `css/aiserik.css` | 18 | what happens without clear |
| Centering technique 1 | `css/base.css` | 118 | absolute + transform |
| Centering technique 2 | `css/base.css` | 154 | margin auto |
| Centering technique 3 | `css/aiserik.css` | 151 | grid `place-items` |

## Still Needed for Submission

- Hand-drawn layout sketch photos for two pages.
- Before styling screenshot.
- After styling screenshot.
- Updated AI log entry for this work.
- W3C HTML and CSS validator checks.
