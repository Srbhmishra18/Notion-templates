# Notion Templates

## German Vocabulary Tracking Template (Home + Separate Words/Verbs)

Use this template structure in Notion to create one clean, beginner-friendly **Home page** with two quick actions:
- **Add Word** (adds item to Words database)
- **Add Verb** (adds item to Verbs database)

Both databases live on separate pages and are managed independently.

---

## 1) Home Page: `German Vocab Tracker 🇩🇪`

### Sections

#### A. Quick Actions (Buttons)
Create two Notion **Button** blocks:

1. **Button Name:** `➕ Add Word`
   - Action: `New page in` → `Words DB`
   - Open: `Side peek` (recommended)
   - Icon color: Blue (easy visual separation)
   - Optional prefill:
      - `Status = New`
      - `Type = Noun`

2. **Button Name:** `➕ Add Verb`
   - Action: `New page in` → `Verbs DB`
   - Open: `Side peek` (recommended)
   - Icon color: Orange (easy visual separation)
   - Optional prefill:
      - `Status = New`
      - `Tense Focus = Present`

Place these buttons at the very top so adding entries is always one click away.

#### B. Navigation
Add links to two separate pages:
- `📘 Words Database`
- `⚡ Verbs Database`

Keep navigation directly under buttons so users always know where to go next.

#### C. Dashboard Views (optional linked databases)
- `🕒 Added This Week` (recent words + verbs)
- `✅ Review Today` (Next Review is today or earlier)
- `🔥 Hard Items` (Difficulty >= 4)

#### D. Friendly UI polish (recommended)
- Add short helper text under the page title: `Track words daily. Review little and often.`
- Use callouts for tips:
  - `Blue callout`: How to add new words
  - `Orange callout`: How to review verbs
- Keep only the 3 most useful dashboard views on Home to reduce clutter.

---

## 2) Page: `📘 Words Database`

Create a **Table - Full page** database with these properties:

- `Word` (Title)
- `Article` (Select: der / die / das / —)
- `Plural` (Text)
- `Meaning (EN)` (Text)
- `Example Sentence` (Text)
- `Example Translation` (Text)
- `Type` (Select: Noun / Adjective / Adverb / Phrase / Other)
- `Level` (Select: A1 / A2 / B1 / B2 / C1)
- `Topic` (Multi-select: Travel, Work, Food, Feelings, etc.)
- `Difficulty` (Number 1-5)
- `Status` (Select: New / Learning / Review / Mastered)
- `Last Reviewed` (Date)
- `Next Review` (Date)
- `Notes` (Text)

Suggested views:
- `All Words` (table)
- `Need Review` (filter: Next Review is today or earlier)
- `New This Week` (filter: Created time is within past week)
- `Mastered` (filter: Status = Mastered)

Recommended sort order:
- `Need Review`: Next Review ascending
- `All Words`: Last Reviewed descending

---

## 3) Page: `⚡ Verbs Database`

Create a separate **Table - Full page** database with these properties:

- `Verb (Infinitive)` (Title)
- `Meaning (EN)` (Text)
- `Regular/Irregular` (Select: Regular / Irregular)
- `Auxiliary Verb` (Select: haben / sein)
- `Past Participle` (Text)
- `3rd Person Präsens` (Text)
- `Präteritum` (Text)
- `Reflexive` (Checkbox)
- `Case/Preposition` (Text)
- `Example Sentence` (Text)
- `Example Translation` (Text)
- `Separable` (Checkbox)
- `Tense Focus` (Select: Present / Perfect / Präteritum / Konjunktiv)
- `Difficulty` (Number 1-5)
- `Status` (Select: New / Learning / Review / Mastered)
- `Last Reviewed` (Date)
- `Next Review` (Date)
- `Notes` (Text)

Suggested views:
- `All Verbs` (table)
- `Irregular Verbs` (filter: Regular/Irregular = Irregular)
- `Review Queue` (filter: Next Review is today or earlier)
- `Recently Added` (filter: Created time is within past week)

Recommended sort order:
- `Review Queue`: Next Review ascending
- `All Verbs`: Last Reviewed descending

---

## 4) Usage Flow
1. Open `German Vocab Tracker 🇩🇪`.
2. Click `➕ Add Word` for nouns/adjectives/phrases.
3. Click `➕ Add Verb` for verbs and conjugation details.
4. Review from each database page using `Need Review`/`Review Queue` views.

This setup gives you one clean home page, faster input actions, simpler navigation, and less visual clutter.
