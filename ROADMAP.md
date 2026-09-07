# Roadmap

Language Ladder will grow from a small, carefully reviewed phrasebook into a
reusable curriculum and learning resource for many languages.

## Current focus

- Establish the English lesson and vocabulary templates.
- Build the first Arabic lessons using Modern Standard Arabic, with dialect
  labeling where relevant.
- Expand comparison tables from supported practice to target-language-only
  exercises.
- Add more home, classroom, food, and everyday vocabulary.

## Next steps

- Add lessons 2 and 3 for descriptions, locations, routines, requests, and
  polite responses.
- Add answer-key conventions for hiding English support in future tools.
- Define a consistent source and reviewer format for language entries.
- Add another target language to test which parts of the structure are universal
  and which need language-specific extensions.

## Later possibilities

- Searchable vocabulary by lesson, location, part of speech, and difficulty.
- Audio and pronunciation review contributed by fluent speakers.
- Interactive exercises that gradually hide translations and transliteration.
- Progress tracking and spaced review.
- A small web or command-line tool generated from the Markdown resources.

The roadmap is a direction, not a promise. Accuracy, learner safety, and useful
content should come before breadth.

```
language-ladder/
├── README.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── LICENSE
├── AUTHORS.md
├── ROADMAP.md
│
├── docs/                        # Project-level documentation
│ ├── philosophy.md              # Learning approach & progressive ladder
│ ├── curriculum-levels.md       # Clear definition of Lesson 1→5 + beyond
│ ├── content-guidelines.md      # How to write good entries
│ ├── stages.md                  # Supported / Guided / Independent explained
│ └── adding-a-language.md       # Step-by-step for new languages
│
├── core/                        # Language-agnostic foundation
│ ├── templates/                 # Master templates (copy these)
│ │ ├── lesson-template.md
│ │ ├── vocabulary-entry.md
│ │ ├── phrase-template.md
│ │ └── location-template.md
│ ├── concepts/                  # Shared concepts (not language-specific)
│ │ ├── objects.md
│ │ ├── people.md
│ │ ├── actions.md
│ │ ├── numbers.md
│ │ ├── colors.md
│ │ └── ...
│ └── curriculum/                # The actual learning path (English meaning)
│ ├── lesson-01-first-words.md
│ ├── lesson-02-descriptions.md
│ ├── lesson-03-daily-needs.md
│ ├── lesson-04-connected-speech.md
│ └── lesson-05-fluency-culture.md
│
├── languages/                   # All target languages live here
│ ├── en/                        # English = reference + learner materials
│ │ ├── README.md
│ │ ├── meta.yaml                # language code, name, script direction, etc.
│ │ ├── lessons/
│ │ ├── vocabulary/
│ │ ├── locations/
│ │ ├── phrases/
│ │ └── culture/                 # Optional early culture notes
│ │
│ ├── ar/                        # Arabic (first real target)
│ │ ├── README.md
│ │ ├── meta.yaml
│ │ ├── lessons/
│ │ ├── vocabulary/
│ │ ├── locations/
│ │ ├── phrases/
│ │ ├── culture/                 # Nativity, dialects, politeness, real situations
│ │ └── dialects/                # Optional: egyptian.md, levantine.md, etc.
│ │
│ └── [future languages]/
│
├── shared/                      # Cross-language reusable assets
│ ├── images/                    # Optional illustrations
│ ├── audio/                     # Future pronunciation recordings
│ └── schemas/                   # JSON/YAML schemas for validation (optional)
│
└── tools/                       # Future scripts & generators (keep empty for now)
└── README.md
```
