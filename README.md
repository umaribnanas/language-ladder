# Language Ladder

A practical, community-built phrasebook and curriculum for learning languages
from first words to natural conversation.

Language Ladder begins with English as a reference, then grows into resources
for other languages. It is designed to make learning gradual: learners start
with familiar words and visible translations, then steadily move towards
understanding and speaking the target language on its own terms.

This repository currently uses Arabic as its first target language. The structure
is intentionally broader than Arabic or English, so contributors can record the
grammar, scripts, pronunciation, politeness, dialects, and cultural context
that make each language unique.

Language Ladder is also looking for maintainers and long-term contributors. The
project should remain useful even when its original author is busy or no longer
able to participate regularly. If you care about language learning, language
accuracy, documentation, or the future of this resource, you are welcome to
help shape and carry it forward.

## Start here

- Read the [first English lesson](en/lessons/lesson-01-first-words.md) to see
  the source template.
- Compare it with the [Arabic lesson](ar/lessons/lesson-01-first-words.md) to
  see how a target language adds script, pronunciation, and grammar notes.
- Browse the [object vocabulary](en/vocabulary/objects.md) and the [home
  vocabulary](ar/locations/home.md) for reusable examples.
- Use the [contribution guide](CONTRIBUTING.md) to add a language,
  lesson, phrase, or carefully reviewed word.

## Project documents

- [Contributing](CONTRIBUTING.md) - contribution workflow, content standards,
  and review guidance.
- [Authors and contributors](AUTHORS.md) - project attribution and contributor
  credit.
- [Code of conduct](CODE_OF_CONDUCT.md) - expectations for respectful,
  constructive collaboration.
- [Roadmap](ROADMAP.md) - current priorities and possible future tools.

The project is available under the [MIT License](LICENSE). Review the license
before redistributing the learning materials or any future software built from
this repository.

## Our approach

- Start with high-frequency, concrete language and build towards useful sentences.
- Reuse words across templates, lessons, and locations rather than translating
  the same word in isolation each time.
- Record meaning and usage, not only a one-to-one translation.
- Keep standard language, dialect, register, gender, and cultural context
  visible when they affect what a learner should say.
- Prefer natural translations over forcing a target language into English
  grammar.

## Repository layout

```text
en/                         English reference templates
   lessons/                Progression from simple to complex
   locations/              Home, school, restaurant, and other settings
   vocabulary/             Reusable concepts and example words
ar/                         Arabic learner resources
   lessons/                Arabic versions of the lessons
   locations/              Arabic vocabulary grouped by setting
   vocabulary/             Arabic entries with script and pronunciation
```

The English files describe the learning intent. A target-language folder should
mirror that intent, but it may add fields or files when the language needs them.

## Entry format

Use this format for reusable vocabulary entries:

```markdown
### book

- Meaning: a bound set of pages used for reading
- Target: كتاب
- Transliteration: kitaab
- Part of speech: noun
- Grammar: masculine; plural كتب (kutub)
- Register: neutral / standard
- Examples: This is a book.
- Notes: Add a dialect variant when it is common or changes the meaning.
```

Use this format for phrases and templates:

```markdown
### Template: This is [thing].

- Goal: identify a nearby object
- Pattern: This is [noun].
- Example: This is a book.
- Target: هذا [noun].
- Substitutions: book, chair, house
- Grammar note: document agreement or word-order changes here
- Culture note: document politeness, taboo, or context here
```

These fields are a guide, not a constraint. A language-specific explanation is
more valuable than a misleadingly symmetrical translation.

## Progressive comparison tables

A comparison table is useful at the start of a lesson, but it should be a
scaffold rather than the final exercise. Keep the columns stable while changing
which columns the learner sees:

| Stage       | Learner sees                                                                 | Activity                                                          |
| ----------- | ---------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Supported   | English, target script, pronunciation, meaning                               | Match and repeat the phrase.                                      |
| Guided      | Target script and pronunciation; English is covered or shown after answering | Read aloud and substitute a new word.                             |
| Independent | Target script only                                                           | Understand, answer, or produce the phrase in the target language. |

Use an answer key or collapsible section in a future app to reveal the hidden
columns. In Markdown, label the intended stage and keep the full comparison
available for teachers and reviewers. Do not remove grammar or culture notes
just to make the columns symmetrical.

Recommended comparison columns:

```markdown
| English         | Target script | Pronunciation  | Literal structure                       | Stage     |
| --------------- | ------------- | -------------- | --------------------------------------- | --------- |
| This is a book. | هذا كتاب.     | haadhaa kitaab | this + book; present "is" is understood | Supported |
```

## Curriculum levels

Lessons should grow in small, observable steps:

1. **Lesson 1: first words** - people, objects, yes/no, greetings, and simple
   pointing or naming.
2. **Lesson 2: short descriptions** - possession, location, colors, numbers,
   and basic questions.
3. **Lesson 3: daily needs** - food, school, home routines, requests, and
   polite responses.
4. **Lesson 4: connected speech** - time, reasons, preferences, past and
   future events, and short conversations.
5. **Lesson 5: real-world fluency** - idioms, regional variants, written versus
   spoken language, and culture-specific situations.

Each lesson should link to the vocabulary it introduces and revisit words from
earlier lessons. Locations are contexts, not difficulty levels: a restaurant
file can contain both beginner naming exercises and advanced ordering dialogue.

## Arabic notes

Arabic resources should distinguish Modern Standard Arabic (MSA) from spoken
dialects. The starter material uses MSA unless it says otherwise. Arabic nouns
have grammatical gender, and demonstratives and adjectives agree with nouns;
this is why a template may need more than one target-language form. Arabic is
written right-to-left, while transliteration is only a pronunciation aid and
should never replace the Arabic script.

The Arabic definite article is written `الـ` and can affect pronunciation with
sun letters. Add this kind of pronunciation note only where it helps a learner,
and label regional forms rather than presenting one dialect as universal.

## Contributing a language

Contributions of every size are welcome, whether you are a language teacher,
student, native speaker, developer, or careful reviewer. You can improve the
structure, add a lesson, contribute a few words, or clarify a usage note.

We are especially interested in people who can help maintain the project over
time. Maintainers may review contributions, guide the curriculum, support
language-specific reviewers, improve the repository structure, and help make
decisions when the project grows. Shared stewardship is encouraged: the future
of this resource should not depend on one person always being available.

To add a language, start by copying the intent of an English lesson, then add:

- native script and a consistent pronunciation system;
- literal meaning and natural meaning where they differ;
- gender, number, classifiers, cases, or other grammar that affects reuse;
- register and dialect labels;
- cultural notes, usage warnings, and examples from real situations;
- a source or reviewer note for uncertain, disputed, or region-specific forms.

Avoid machine-translating a whole folder without review. A small set of checked,
natural examples is better learning material than a large set of literal ones.

When possible, include the language variety, region, register, and source or
reviewer for forms that are uncertain, disputed, or context-dependent. This
helps learners and future contributors understand not only what to say, but
when and why to say it.
