# THE MINUTES

**THE MINUTES** is a single-page text tool from the **SPARK TOOLS** suite.

It generates corrective “minutes” for everyday scenes, institutions, rituals, documents, and social performances. Each entry contrasts the official version of events with the quieter record underneath.

## Concept

Every room produces two records.

One is the acceptable version: polite, procedural, stable, easy to file.

The other is what actually happened: the labour hidden inside the routine, the pressure disguised as kindness, the hierarchy inside the joke, the omission that made the official record possible.

**THE MINUTES** reads the second document.

## Core Format

Each card follows the same structure:

```text
On record: [the official version]. Minutes: [the corrective record].
```

Example:

```text
On record: the exchange stayed friendly. Minutes: one person edited the truth to keep the peace.
```

The format is deliberately simple. The first clause gives the public record. The second clause amends it.

## Interaction

The app is built around one primary action:

**READ ENTRY**

Pressing the button generates one entry from the deck.

The user can then:

* **COPY** the entry
* **CLEAR** the current card
* open **ABOUT**
* return to the main view

Copied text includes the card and the app name:

```text
On record: the exchange stayed friendly. Minutes: one person edited the truth to keep the peace.

THE MINUTES
```

## Current Deck

The current deck contains:

* **999 cards**
* event-register cards
* document/register cards
* aftermath/time/history cards
* domestic, institutional, civic, workplace, cultural, and public settings
* no user input
* no saved records
* no tracking

The deck was audited for:

* exact duplicates
* repeated record headings
* delimiter consistency
* hard character cap
* register balance
* domain spread
* British spelling
* curly punctuation
* boundary from BAD EVIDENCE-style proof cards

## Design Direction

THE MINUTES belongs visually to the SPARK TOOLS family: dark terminal shell, strong title treatment, compact interaction, and a central output object.

Its specific visual identity is:

**filed document / amended record**

The screen should feel like an official page being contradicted.

Design principles:

* dark archival interface
* warm paper card
* ruled document texture
* green **ON RECORD:** label
* red **MINUTES:** label
* black body text
* red amendment impact
* simple document icon
* restrained animation
* mobile-first layout

The app should feel sharp, procedural, slightly hostile, and quietly funny. It should not feel like a generic quote generator.

## Text Standards

Cards should be:

* clear at first reading
* under the hard character limit
* specific rather than vague
* socially observant without becoming preachy
* funny through precision, not randomness
* readable as minutes, not slogans
* distinct from BAD EVIDENCE, BADVICE, or DEADWEIGHT
* free of sentimental overstatement
* free of generic self-help language

Avoid:

* “proof that…” logic
* therapy-speak
* corporate abstraction
* overly cute metaphors
* repeated openings
* repeated second-line structures
* obvious moralising
* lines that sound like captions rather than records

Preferred standard:

```text
On record: the apology was carefully balanced. Minutes: balance gave the harmed person grammar instead of repair.
```

## Technical Notes

THE MINUTES is a single-file HTML app containing:

* HTML structure
* CSS styling
* JavaScript engine
* full card deck

No build step is required.

No external database is required.

The app runs locally in any modern browser.

## Deck Editing Rules

Cards are stored in the JavaScript `CARDS` array.

Each card must contain exactly:

* one `On record:`
* one `Minutes:`

Example:

```js
"On record: the exchange stayed friendly. Minutes: one person edited the truth to keep the peace.",
```

Before release, validate:

* total deck count
* exact uniqueness
* unique record headings
* single delimiter structure
* maximum character length
* no unwanted spillover from other SPARK TOOLS apps
* correct copy output
* working READ ENTRY / COPY / CLEAR / ABOUT controls

## Relationship to SPARK TOOLS

THE MINUTES is part of a wider family of compact text tools.

Its role in the suite:

* **DEADWEIGHT** drops unnecessary weight.
* **BAD EVIDENCE** exposes false proof.
* **TILT** bends certainty.
* **BADVICE** gives terrible advice beautifully.
* **IDK MACHINE** generates creative starting points.
* **THE MINUTES** amends the official record.

It is the suite’s corrective log.

## Intended Use

THE MINUTES can be used for:

* writing prompts
* social observation
* satire
* workshop exercises
* dialogue development
* institutional critique
* creative journalling
* cultural commentary
* character and scene generation
* playful forensic thinking

It works best when the user asks:

> What did the official version leave out?

## Privacy

THE MINUTES runs entirely in the browser.

It does not collect, transmit, analyse, or store user data.

No account, server, analytics layer, or external service is required.

## Status

Current version:

* 999-card complete deck
* hostile-audited text pass
* refined SPARK TOOLS visual system
* green/red label hierarchy
* amended-record visual identity
* working copy logic
* single-file HTML prototype

## Licence

All rights reserved unless otherwise specified by the creator.
