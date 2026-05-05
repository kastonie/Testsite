# Lily's World 🐾

> The official website of Lily — 8-year-old Mini Schnauzer, professional napper, certified bath-time escape artist.

**Live site:** https://kastonie.github.io/Testsite/

---

## Developer Documentation

### System Requirements

Before contributing to this repository, ensure your environment meets the following requirements:

- **Nose:** Functional. Must be capable of sniffing out bugs.
- **Paws:** 4 recommended. 2 minimum (for typing).
- **Nap schedule:** At least 14 hours/day. Under-rested contributors produce unstable code.
- **Treat buffer:** Keep local snack cache stocked at all times. Low blood sugar causes merge conflicts.
- **Zoomie RAM:** Reserve at least one (1) unscheduled zoomie burst per afternoon for creative problem solving.

---

### Installation

```bash
# Clone the repository
git clone https://github.com/kastonie/Testsite.git

# Navigate to project directory
cd Testsite

# Sniff the directory thoroughly before proceeding
sniff .

# Install dependencies
# There are no dependencies. Go nap. You earned it.
```

---

### Architecture Overview

This project follows a **Single Paw File (SPF)** architecture — all logic, styles, and markup live in one `index.html`. This is intentional. Separating files across multiple directories is stressful and makes it harder to nap between deployments.

```
Testsite/
├── index.html        # The whole thing. Do not touch while sleeping.
├── images/           # Photos of Lily. Handle with care. She is very cute.
│   ├── lily-smiling.jpeg
│   ├── lily-pajamas.jpeg
│   ├── lily-dog-bed.jpeg
│   └── ...
└── README.md         # You are here. Good dog.
```

---

### Core Concepts

#### The Treat-Driven Development (TDD) Model

All features are prioritized using the **Treat-Driven Development** methodology:

1. Sniff the problem
2. Bark at it twice
3. Stare at it until a human fixes it
4. Accept treat
5. Nap
6. Deploy

#### State Management

Global state is stored in `localStorage`. If `localStorage` is full, clear it by spinning in a circle three times and sitting down firmly.

#### The Bath Avoidance Protocol (BAP)

Under no circumstances should the word **"bath"** appear in any `console.log`, variable name, or commit message. Violations will trigger the easter egg and the entire engineering team will scatter.

---

### API Reference

#### `shareLily()`
Invokes the device's native share sheet to spread awareness of Lily.

**Parameters:** None. Lily requires no parameters. She simply is.

**Returns:** `Promise<void>` — resolves after sharing, or after the user dismisses the dialog to go pet their own dog instead.

---

#### `playBark()`
Synthesizes an authentic woof using the Web Audio API.

**Parameters:** None.

**Side effects:** May cause nearby dogs to look up from their nap.

**Known issue:** Does not actually alert the mailman.

---

#### `triggerBathEasterEgg()`
Activated by typing `bath` anywhere on the page. Causes Lily to sprint across the screen at maximum velocity.

**Do not call this function directly.** Lily will know. She always knows.

---

#### `toggleRetro()`
Switches between modern design and authentic 1997 GeoCities aesthetic.

**Parameters:** None.

**Browser support:** Netscape Navigator 4.0+, Internet Explorer 5+, modern browsers (reluctantly).

---

### Deployment

This project deploys automatically to GitHub Pages on every push to `main`.

**Estimated deploy time:** 1–2 minutes, which is approximately 7–14 minutes in dog time. Please be patient. Have a snack.

---

### Contributing

Pull requests are welcome, provided the contributor:

1. Has reviewed the codebase with their nose
2. Has not recently said the B-word
3. Is not currently in zoomie mode (unstable typing)
4. Has not eaten in the last 10 minutes (hunger causes aggressive refactoring)

All PRs require approval from **@lily** — she reviews by sitting on the keyboard. If your PR contains typos, that was her feedback.

---

### Known Issues

| Issue | Status | Notes |
|-------|--------|-------|
| Lily will not attend standups | `wontfix` | She has a scheduling conflict (nap) |
| Bath section causes distress | `by design` | This is a feature |
| Desk supervisor bites reviewer | `wontfix` | Work-life balance enforcement |
| Squirrel detected outside window | `critical` | All work halted. Investigating. |

---

### License

This project is licensed under the **Paw Public License (PPL)**.

You are free to:
- View the site
- Share the site
- Tell your friends about Lily

You are **not** permitted to:
- Say the B-word
- Interrupt a nap
- Pretend your dog is cuter than Lily

---

*Documentation last updated by Lily. She was asleep during production.*
