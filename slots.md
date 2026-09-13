# Slot reference for category: business.lifestyle

The FreeWebStore platform AI rewrites your template per small business by
filling `data-fws-slot` attributes. The slots below are the *conventional*
set for **business.lifestyle** — using them gives the platform AI
deterministic anchors, so customization is predictable.

Templates *without* slot markers still work — the AI infers structure from
the HTML — but marked templates are more reliable and easier to QA.

## Universal slots (all categories)

| Slot | Element type | What goes there |
|------|--------------|-----------------|
| `business.name` | text | Legal or display name of the business |
| `business.tagline` | text | One-line pitch, shown in the hero |
| `about.body` | rich text | 2-4 sentence about-the-business paragraph |
| `contact.address` | text | Street address |
| `contact.phone` | text | Phone number, formatted |
| `contact.email` | text | Public email |
| `contact.hours` | text or list | Opening hours |
| `fws.byline` | reserved | DO NOT EDIT — the platform writes the designer credit here |

## Lifestyle-specific slots used by this template

| Slot | Where |
|------|-------|
| `campaign.hero.description` | Hero supporting copy |
| `card.1.title` … `card.4.title` | Card studio design titles |
| `card.1.desc` … `card.4.desc` | Card studio design descriptions |
| `fact.1.label` … `fact.4.label` | Statistics captions |
| `save.title` | Save-the-Date heading |
| `save.description` | Save-the-Date supporting copy |
| `save.note` | Save-the-Date fine-print note |
| `calendar.update.1` … `calendar.update.4` | Announcement ribbon feed items |
| `help.1.title` … `help.3.title` | Atelier help card titles |

See the per-category SLOT-SCHEMAS reference in the platform docs for the
full list.