# 📚 100% Zero-Key Public NLP, Dictionary & Knowledge APIs

This document indexes 10 directly callable endpoints for language processing, semantic word search, entity lookup, demographic inference, and trivia feeds. Developers can query dictionaries, Wikipedia knowledge cards, semantic associations, and translation services instantly via standard GET/POST methods without API tokens or developer registrations.

---

## 📋 Quick Technical Reference

| Service Name | Method | Base URL / Call | Auth Required | Private Token Setup |
|---|---|---|---|---|
| FreeDictionary | GET | https://api.dictionaryapi.dev/api/v2/entries/en/{word} | None | 0% (No key needed) |
| Datamuse Query | GET | https://api.datamuse.com/words?ml={query} | None | 0% (No key needed) |
| Wikipedia REST | GET | https://en.wikipedia.org/api/rest_v1/page/summary/{topic} | None | 0% (No key needed) |
| Agify.io | GET | https://api.agify.io?name={name} | None | 0% (No key needed) |
| Genderize.io | GET | https://api.genderize.io?name={name} | None | 0% (No key needed) |
| Nationalize.io | GET | https://api.nationalize.io?name={name} | None | 0% (No key needed) |
| LibreTranslate | POST | https://libretranslate.de/translate | None | 0% (No key needed) |
| Numbers Trivia | GET | http://numbersapi.com/random/trivia | None | 0% (No key needed) |
| Numbers Math | GET | http://numbersapi.com/random/math | None | 0% (No key needed) |
| Universities List | GET | http://universities.hipolabs.com/search?name={query} | None | 0% (No key needed) |

---

## 🌐 Instant Cloud Endpoints (Direct Web & cURL Access)

### 1. FreeDictionary API
- Endpoint: GET https://api.dictionaryapi.dev/api/v2/entries/en/{word}
- Output: Definitions, parts of speech, phonetic spellings, and audio pronunciations.
- Token Requirement: Zero developer registration or private API keys required.
- Direct cURL Execution:
  curl https://api.dictionaryapi.dev/api/v2/entries/en/technology

### 2. Datamuse Semantic Word Association
- Endpoint: GET https://api.datamuse.com/words?ml={query}
- Output: Semantic word embeddings, rhymes, synonyms, and related vocabulary terms.
- Token Requirement: Zero developer registration or private API keys required.
- Direct cURL Execution:
  curl "https://api.datamuse.com/words?ml=artificial+intelligence"

### 3. Wikipedia REST Summary Endpoint
- Endpoint: GET https://en.wikipedia.org/api/rest_v1/page/summary/{topic}
- Output: Direct knowledge snippets, extract text, and preview thumbnails for any topic.
- Token Requirement: Zero developer registration or private API keys required.
- Direct cURL Execution:
  curl https://en.wikipedia.org/api/rest_v1/page/summary/Computer_science

### 4. Agify.io Name Age Predictor
- Endpoint: GET https://api.agify.io?name={name}
- Output: Estimated demographic age prediction based on historical record frequency.
- Token Requirement: Zero developer registration or private API keys required.
- Direct cURL Execution:
  curl https://api.agify.io?name=Alex

### 5. Genderize.io Name Gender Inference
- Endpoint: GET https://api.genderize.io?name={name}
- Output: Probability score and predicted gender classification for any given name.
- Token Requirement: Zero developer registration or private API keys required.
- Direct cURL Execution:
  curl https://api.genderize.io?name=Michael

### 6. Nationalize.io Nationality NLP Predictor
- Endpoint: GET https://api.nationalize.io?name={name}
- Output: Country probability matrix estimating nationality distribution for names.
- Token Requirement: Zero developer registration or private API keys required.
- Direct cURL Execution:
  curl https://api.nationalize.io?name=Raj

### 7. LibreTranslate Public Direct Instance
- Endpoint: POST https://libretranslate.de/translate
- Output: Neural machine translation across multiple languages.
- Token Requirement: Zero developer registration or private API keys required on public tier.
- Direct cURL Execution:
  curl -X POST "https://libretranslate.de/translate" -H "Content-Type: application/json" -d '{"q": "Hello world", "source": "en", "target": "es"}'

### 8. Numbers API Trivia Engine
- Endpoint: GET http://numbersapi.com/random/trivia
- Output: Direct plain text facts and historical trivia associated with numbers.
- Token Requirement: Zero developer registration or private API keys required.
- Direct cURL Execution:
  curl http://numbersapi.com/random/trivia

### 9. Numbers API Math Facts
- Endpoint: GET http://numbersapi.com/random/math
- Output: Mathematical properties and numerical curiosity facts returned as plain text.
- Token Requirement: Zero developer registration or private API keys required.
- Direct cURL Execution:
  curl http://numbersapi.com/random/math

### 10. Universities NLP Directory
- Endpoint: GET http://universities.hipolabs.com/search?name={query}
- Output: Global higher education institution dataset with verified web domains.
- Token Requirement: Zero developer registration or private API keys required.
- Direct cURL Execution:
  curl "http://universities.hipolabs.com/search?name=Stanford"

---

## 🏢 Curated By

Curated and structured by RudraX Technologies Studio (https://rudraxstudio.freedev.app)[span_0](start_span)[span_0](end_span).

### ⚠️ Third-Party Attribution & Service Notice
- Third-Party Ownership: All third-party endpoints, models, datasets, and linguistic dictionaries referenced above belong strictly to their respective creators, providers, and open-source communities.
- Directory Role: RudraX Technologies Studio does not own, build, or operate these external services[span_1](start_span)[span_1](end_span). Our sole contribution is centralizing verified, 100% keyless options into one catalog to help developers build projects without authentication friction[span_2](start_span)[span_2](end_span).
