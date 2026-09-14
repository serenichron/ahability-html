# ahability-html

Two hand-coded landing pages for Ahability, a Romanian clinical psychology practice.

| File | Page |
| --- | --- |
| `index.html` | Parenting programme. A reproduction of the client's Thrive Architect page at ahability.ro/landing-page-v2. |
| `sedinte-individuale.html` | Individual online sessions for adults. Written from a brief, not a reproduction. |

Open either file in a browser. There is no build step.

## Stylesheets

`style.css` holds everything both pages share, including the footer.
`style-individual.css` loads after it and only adds what the individual-sessions page needs.
Edit shared rules in `style.css` so the two pages cannot drift apart.

## External dependencies

Loaded from CDNs at runtime: Bootstrap 5.3.3, Bootstrap Icons 1.11.3, and Google Fonts
(Titillium Web, Dancing Script, Figtree). The parenting page also pulls three emoji SVGs
from s.w.org, matching the original.

## Before this goes live

Placeholders marked in the markup still need real values.

- `[NUME]` and `[DE COMPLETAT]`: Liana's surname and her Colegiul Psihologilor registration code.
- `[PLATFORMĂ]`: the video platform used for sessions.
- The session price on `sedinte-individuale.html` is set to 150 lei.
- Booking link, privacy policy, terms and contact links all point at `#`.
- Photos in `images/` named `ph-*.jpg` are Unsplash placeholders and need replacing.

The individual-sessions copy was checked against the Colegiul Psihologilor din România
code of ethics, in particular Articles IV.29 to IV.32 on advertising. Keep that in mind
when editing claims about results, methods, or comparisons with other practitioners.
