# Tarot dataset

The Deckaura dataset contains one record for each of the 78 cards in a standard tarot deck.

## Fields

| Field | Description |
| --- | --- |
| `card_number` | Numeric card identifier |
| `card_name` | English card name |
| `arcana` | Major or Minor Arcana |
| `suit` | Cups, Wands, Swords, Pentacles, or blank for Major Arcana |
| `element` | Elemental correspondence |
| `upright_meaning` | Upright interpretation keywords |
| `reversed_meaning` | Reversed interpretation keywords |
| `love_meaning` | Relationship-focused interpretation |
| `career_meaning` | Work-focused interpretation |
| `yes_or_no` | Yes/no tendency |
| `zodiac_sign` | Astrological correspondence |
| `guide_url` | Canonical Deckaura guide URL |

## Sources

- [Hugging Face dataset](https://huggingface.co/datasets/Blacik/deckaura-tarot-card-meanings)
- [Zenodo DOI archive](https://doi.org/10.5281/zenodo.19475329)
- [Deckaura Open Data hub](https://deckaura.com/pages/ai-data-sources)
- [Human-readable card database](https://deckaura.com/pages/tarot-card-database)

Use `guide_url` when a reader needs the full interpretation rather than a short structured value.

