# LocalTranslate language packs

Language packs for **LocalTranslate**: offline translation models that the app downloads and installs from **Settings → Languages → Download**.

Each pack adds one language, translated to and from English (other pairs go through English). The models are [OPUS-MT](https://github.com/Helsinki-NLP/Opus-MT) by Helsinki-NLP (University of Helsinki), converted to CTranslate2 int8. The files are unchanged otherwise, and every file is SHA-256 checked by the app before installation.

| Language | File | Size | Pairs | Models (license) |
|---|---|---|---|---|
| Dutch (`nl`) | `LocalTranslate-Languages-nl.zip` | 129 MB | en-nl, nl-en | [Helsinki-NLP/opus-mt-en-nl](https://huggingface.co/Helsinki-NLP/opus-mt-en-nl) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-nl-en](https://huggingface.co/Helsinki-NLP/opus-mt-nl-en) (Apache-2.0) |
| Russian (`ru`) | `LocalTranslate-Languages-ru.zip` | 130 MB | en-ru, ru-en | [Helsinki-NLP/opus-mt-en-ru](https://huggingface.co/Helsinki-NLP/opus-mt-en-ru) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-ru-en](https://huggingface.co/Helsinki-NLP/opus-mt-ru-en) (CC-BY-4.0) |
| Swedish (`sv`) | `LocalTranslate-Languages-sv.zip` | 127 MB | en-sv, sv-en | [Helsinki-NLP/opus-mt-en-sv](https://huggingface.co/Helsinki-NLP/opus-mt-en-sv) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-sv-en](https://huggingface.co/Helsinki-NLP/opus-mt-sv-en) (Apache-2.0) |
| Danish (`da`) | `LocalTranslate-Languages-da.zip` | 128 MB | da-en, en-da | [Helsinki-NLP/opus-mt-da-en](https://huggingface.co/Helsinki-NLP/opus-mt-da-en) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-en-da](https://huggingface.co/Helsinki-NLP/opus-mt-en-da) (Apache-2.0) |
| Finnish (`fi`) | `LocalTranslate-Languages-fi.zip` | 127 MB | en-fi, fi-en | [Helsinki-NLP/opus-mt-en-fi](https://huggingface.co/Helsinki-NLP/opus-mt-en-fi) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-fi-en](https://huggingface.co/Helsinki-NLP/opus-mt-fi-en) (Apache-2.0) |
| Czech (`cs`) | `LocalTranslate-Languages-cs.zip` | 132 MB | cs-en, en-cs | [Helsinki-NLP/opus-mt-cs-en](https://huggingface.co/Helsinki-NLP/opus-mt-cs-en) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-en-cs](https://huggingface.co/Helsinki-NLP/opus-mt-en-cs) (Apache-2.0) |
| Hungarian (`hu`) | `LocalTranslate-Languages-hu.zip` | 132 MB | en-hu, hu-en | [Helsinki-NLP/opus-mt-en-hu](https://huggingface.co/Helsinki-NLP/opus-mt-en-hu) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-hu-en](https://huggingface.co/Helsinki-NLP/opus-mt-hu-en) (Apache-2.0) |
| Ukrainian (`uk`) | `LocalTranslate-Languages-uk.zip` | 126 MB | en-uk, uk-en | [Helsinki-NLP/opus-mt-en-uk](https://huggingface.co/Helsinki-NLP/opus-mt-en-uk) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-uk-en](https://huggingface.co/Helsinki-NLP/opus-mt-uk-en) (Apache-2.0) |
| Hindi (`hi`) | `LocalTranslate-Languages-hi.zip` | 132 MB | en-hi, hi-en | [Helsinki-NLP/opus-mt-en-hi](https://huggingface.co/Helsinki-NLP/opus-mt-en-hi) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-hi-en](https://huggingface.co/Helsinki-NLP/opus-mt-hi-en) (Apache-2.0) |
| Indonesian (`id`) | `LocalTranslate-Languages-id.zip` | 129 MB | en-id, id-en | [Helsinki-NLP/opus-mt-en-id](https://huggingface.co/Helsinki-NLP/opus-mt-en-id) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-id-en](https://huggingface.co/Helsinki-NLP/opus-mt-id-en) (Apache-2.0) |
| Slovak (`sk`) | `LocalTranslate-Languages-sk.zip` | 130 MB | en-sk, sk-en | [Helsinki-NLP/opus-mt-en-sk](https://huggingface.co/Helsinki-NLP/opus-mt-en-sk) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-sk-en](https://huggingface.co/Helsinki-NLP/opus-mt-sk-en) (Apache-2.0) |
| Greek (`el`) | `LocalTranslate-Languages-el.zip` | 329 MB | el-en, en-el | [Helsinki-NLP/opus-mt-tc-big-el-en](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-el-en) (CC-BY-4.0)<br>[Helsinki-NLP/opus-mt-en-el](https://huggingface.co/Helsinki-NLP/opus-mt-en-el) (Apache-2.0) |
| Turkish (`tr`) | `LocalTranslate-Languages-tr.zip` | 275 MB | en-tr, tr-en | [Helsinki-NLP/opus-mt-tc-big-en-tr](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-en-tr) (CC-BY-4.0)<br>[Helsinki-NLP/opus-mt-tr-en](https://huggingface.co/Helsinki-NLP/opus-mt-tr-en) (Apache-2.0) |
| Bulgarian (`bg`) | `LocalTranslate-Languages-bg.zip` | 277 MB | bg-en, en-bg | [Helsinki-NLP/opus-mt-bg-en](https://huggingface.co/Helsinki-NLP/opus-mt-bg-en) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-tc-big-en-bg](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-en-bg) (CC-BY-4.0) |
| Hebrew (`he`) | `LocalTranslate-Languages-he.zip` | 277 MB | en-he, he-en | [Helsinki-NLP/opus-mt-en-he](https://huggingface.co/Helsinki-NLP/opus-mt-en-he) (Apache-2.0)<br>[Helsinki-NLP/opus-mt-tc-big-he-en](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-he-en) (CC-BY-4.0) |

Total: 2.5 GB.

## Attribution and licenses

Models © Helsinki-NLP, OPUS-MT project: Jörg Tiedemann and Santhosh Thottingal, "OPUS-MT — Building open translation services for the World", EAMT 2020. Licensed under Apache-2.0 or [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/), as listed per model above; the license of each pair is also in the `manifest.json` of the pack. Changes: conversion to CTranslate2 with int8 quantization.

## For maintainers

Packs are built with `scripts/package-languages.ps1` of the LocalTranslate repository. The app always downloads from the **latest** release: publish new packs in a new release marked *Latest*, with the same file names, and update `packBytes` in `LanguageCatalog.json`.
