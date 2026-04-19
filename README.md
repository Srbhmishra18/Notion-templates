# Notion Templates

## German Vocabulary Tracking Template (Home + Separate Words/Verbs)

Use this template structure in Notion to create one **Home page** with two button actions:
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
   - Optional prefill:
     - `Status = New`
     - `Type = Noun`

2. **Button Name:** `➕ Add Verb`
   - Action: `New page in` → `Verbs DB`
   - Open: `Side peek` (recommended)
   - Optional prefill:
     - `Status = New`
     - `Tense Focus = Present`

#### B. Navigation
Add links to two separate pages:
- `📘 Words Database`
- `⚡ Verbs Database`

#### C. Dashboard Views (optional linked databases)
- Recent words added this week
- Verbs needing review today
- Difficult items (Difficulty >= 4)

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
- `Mastered` (filter: Status = Mastered)

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

---

## 4) Usage Flow
1. Open `German Vocab Tracker 🇩🇪`.
2. Click `➕ Add Word` for nouns/adjectives/phrases.
3. Click `➕ Add Verb` for verbs and conjugation details.
4. Review from each database page using `Need Review`/`Review Queue` views.

This setup gives you one clean home page and two clearly separated vocab systems.
