# Contributing to SilentScienceProject

SilentScienceProject is an open‑source collaborative library of Grach‑Bailly pictograms designed to make scientific concepts accessible to non‑verbal children.  
Parents, educators and therapists are welcome to contribute new pictograms, translations or improvements.

---

## 🌍 How you can contribute

You can contribute in three ways:

- Add a new pictogram  
- Improve an existing pictogram  
- Add or update translations and keywords  

All contributions must follow the rules below.

---

## 🎨 1. Creating a pictogram

All pictograms must follow the **Grach‑Bailly visual rules**:

- thick black lines  
- solid shapes  
- no perspective  
- no shading  
- no unnecessary detail  
- simple, readable silhouettes  

**File format:**  
- PNG  
- black lines on white background  
- filename in **English** (example: `meteor.png`, `volcano.png`)

Place your file in:

```text
/pictograms
```
---

## 🌐 2. Adding multilingual keywords

To make pictograms searchable in French, English and other languages, update:

### a) `keywords.json`

Add keywords for each language:

```json
"meteor": {
  "en": ["meteor"],
  "fr": ["météore"]
}
```

### b) `/i18n/fr.json`
Add the main French translation:

```json
"meteor": "météore"
```

### c) `/i18n/en.json`
Add the main English translation:

```json
"meteor": "meteor"
```
