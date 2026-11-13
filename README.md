# Calliope

A single-file vocabulary flashcard app. Open it in any browser, no install, no account.

**Live:** https://aintareeb.github.io/calliope/

## Features

- **Flashcards:** tap a card to see the meaning. Only one card is flipped at a time.
- **Related words:** the flipped card stays where it is, and words with a similar meaning, or a shared synonym or antonym, appear again right after it.
- **Notepad view:** switch from Cards to Notepad for a one-word-per-line list. Tap a word to open its meaning, part of speech, preposition, synonyms, antonyms and example sentence.
- **Preposition field:** store what follows a word, for example *abide* → **by**.
- **Pronunciation:** a speaker button reads the word aloud using your device's built-in voice.
- **Learning / Learned:** move words between the two lists. Long-press a card for move, edit and delete.
- **A–Z and search:** browse by letter, or search words, meanings and synonyms.
- **Data tab:** import words by pasting text, copy all or learned words, and back up or restore everything.

## Importing words

Open the **Data** tab, paste one word per line in this format, then tap **Import words**:

```
abide (verb) — accept or act in accordance with | Preposition: by | Example: You must abide by the rules. | Synonyms: Obey | Antonyms: Defy
```

Everything after the meaning is optional. Words that already exist are skipped.

## Your data

Words are saved in your browser on the device you use, not on a server. To move to another device or keep a copy, use **Data → Copy backup**, then paste it into **Backup & restore** on the other device.

## Hosting

The whole app is `index.html`. To host it yourself, put the file in a GitHub repo and turn on **Settings → Pages → Deploy from a branch → main / (root)**.
