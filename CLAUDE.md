# janithdabare.com

Personal portfolio site for Janith Dabare, Software Engineer at IFS (support, escalations and troubleshooting for IFS Cloud Service Management and Mobile Work Order). Readers are IFS customers, IFS partners and other technical support companies.

## How the site is built

- One static page: `index.html` with inline CSS and a small inline script. No framework, no build step.
- Hosted from this GitHub repo. Every push to `main` goes live.
- Keep it that way unless Janith asks for something bigger.

## Hard rules

- Never put customer names, case numbers (CS0...), colleague names or internal IFS details on the site. Case stories stay anonymised ("a North American utility group", "an oil and gas services company").
- The customer quote keeps a generic attribution until Janith confirms he has permission to name the person.
- No date of birth, student number or transcript.

## Writing style

Copy should read like a person wrote it. Avoid em dashes, groups of three used for rhythm, "not just X but Y", words like delve, pivotal or seamless, inflated claims, and bold-label bullets. Short sentences, plain words, first person.

## Design

- Colours: paper #F4F2F8, paper-2 #EAE5F3, ink #1C1530, ink-soft #564E6B, violet #5B2BD6 (primary), violet-deep #3A1A8F, lilac #DDD3F6, amber #E3A008 (priority chips only), line #D6CFE5, console #1E1733.
- Type: Schibsted Grotesk for everything; JetBrains Mono only inside the case replay console.
- Interactive parts: the case replay console (tabs plus a Replay button), the case story folders (details/summary), the Experience and Education switch, and the contact form. The form builds a mailto link to hello@janithdabare.com; there is no backend.
- The photo is images/janith.jpg, used unedited in the hero and for link previews. Janith wants it kept as it is.
- Left-aligned layout. Don't add fade-in effects to sections; the console replay is the only automatic motion.
- Keep it responsive, keyboard-focus visible, and respect prefers-reduced-motion.
