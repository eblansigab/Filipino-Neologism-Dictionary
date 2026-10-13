| Field | Type | Required? | Description |
|---|---|---:|---|
| `entry_id` | Text | Yes | Permanent unique identifier |
| `headword` | Text | Yes | Word in its recorded spelling |
| `definition` | Text | Yes | Meaning of one dictionary sense |
| `part_of_speech` | Text | No | Noun, verb, adjective, etc. |
| `domain` | Text | No | Mathematics, biology, physics, etc. |
| `etymology` | Text | No | Recorded origin or construction |
| `source_title` | Text | Recommended | Title of the source |
| `source_url` | Text | No | Online source location |
| `status` | Text | Yes | `verified`, `unverified`, or `disputed` |
| `notes` | Text | No | Uncertainty or additional context |



=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
## Dataset Rules

- One row represents one meaning or dictionary sense.
- Every row must have a unique entry_id.
- Headwords and definitions must not be empty.
- Original spelling must be preserved.
- Missing information must remain empty rather than being guessed.
- Unconfirmed entries must be marked unverified.
- Disagreements between sources must be recorded rather than silently removed.