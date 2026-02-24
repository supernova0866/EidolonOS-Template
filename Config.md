# Config Reference

Quick reference for every field in `config.json`.

---

| Field | Type | Description |
|---|---|---|
| `title` | string | Your name or alias. Shown as the big hero text. |
| `desc` | string | Short tagline. Shown under the hero eyebrow. |
| `age` | string / null | Your birthdate. Accepts `DD-MM-YYYY`, `YYYY-MM-DD`, Unix timestamp, or `null` to hide. |
| `quotes` | boolean | Show a rotating quote in the hero. Requires `data/quotes.json`. |
| `about.name` | string | Name shown in the about section title. |
| `about.desc` | string | Bio text shown in the about section. |
| `about.identity` | string | Shown in the identity card. |
| `about.status` | string | Shown in the status card. |
| `about.vibe` | string | Shown in the vibe card. |
| `socials.*` | string / null | Full profile URL. Set `null` or remove to hide that card. |
| `modules.projects` | boolean | Enable projects section. Requires `data/projects.json`. |
| `modules.hobbies` | boolean | Enable hobbies section. Requires `data/things.json`. |
| `modules.discord.enabled` | boolean | Enable Discord presence card. |
| `modules.discord.id` | string | Your Discord user ID. You must join [discord.gg/lanyard](https://discord.gg/lanyard). |
| `navbar` | boolean | Show the side navigation toggle. |
| `theme.default` | string | Default theme on first load. `dark` or `light`. |
| `theme.extras.*` | boolean | Enable extra themes in the switcher. |

---

## Extra Themes

| Key | Name |
|---|---|
| `midnight` | Deep purple dark |
| `sepia` | Warm brown |
| `ivory` | Soft warm light |
| `cobalt` | Deep blue |
| `terminal` | Green on black |
| `cli` | Hacker green with typewriter effect |

---

For full documentation → [EidolonOS Core Repo](https://github.com/supernova0866/EidolonOS)
