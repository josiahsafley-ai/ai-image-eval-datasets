# AI Image Evaluation Datasets

Curated AI-image evaluation datasets for detection, forensics, and robustness testing.

These datasets are designed around a real-world problem: images rarely stay pristine. In practice, images are often recompressed, screenshotted, re-saved, or passed through messaging and device workflows before they are ever analyzed. Most detection models fail on these edge cases.

**[safemedia.tech](https://safemedia.tech)**

---

## 🚨 Latest Update: The "Screenshot Laundering" Tier

We just pushed a massive update to the vault. We have added the **Desktop Screenshot** tier for 7 of the most advanced generative models currently in the wild:
- **Flux 1.1 Pro Ultra Raw** & **Flux 2 Pro**
- **Grok AuroraGPT 1.5**
- **Google Imagen 4**
- **Gemini 3.1**
- **Midjourney v7 & v8**
- **Firefly Image 5**

**The Hardware Capture Pipeline:**
Unlike datasets that use simulated degradation filters, we run these through an automated 10-node physical hardware farm. 
* Images are captured natively on desktop environments to trigger genuine OS-level color-profile shifts and C2PA metadata destruction.
* **Strict Boundary Cropping:** Our scripts mathematically crop every captured screenshot back to the exact original image borders. There are **zero OS UI elements** (no window frames, no taskbars). Your models are forced to learn sub-pixel degradation, preventing them from overfitting on desktop backgrounds.

---

## What the datasets include

The dataset catalog focuses on structured packs built around generators and specific real-world transforms.

Transform coverage includes:
- **Original** (Pristine generation)
- **Desktop Screenshot** (Hardware captured, perfectly cropped)
- **Recompressed** (Social media pipeline degradation)
- **Mobile Screenshot** (Physical device capture)

Each item is packaged with structured metadata (including specific `Device_Type` and `OS_Environment` lineage) so the data can be inspected and parsed consistently.

## Free sample pack (Ideogram 3.0)

A free sample pack is available so anyone can inspect the exact pipeline and structure before buying anything.

The free sample pack:
- includes 75 images generated with Ideogram 3.0
- uses the exact same general layout as the paid packs (Original, Recompressed, Screenshots)
- includes structured JSON/CSV metadata
- has no usage restrictions imposed by safemedia.tech

👉 **[Download the free sample pack at safemedia.tech](https://safemedia.tech)**

## Paid packs

Single paid packs contain 1,100 images for one generator under one specific transform. The free sample pack is intended to demonstrate the same style of packaging and dataset structure used throughout the entire paid catalog.

## Per-item structure

Each record package contains:
- `target.*` (The image file)
- `metadata.json`

Dataset packs also include:
- index files such as `.csv` for quick ingestion
- readme/instruction files
- transform/grouping information and device hardware lineage in the metadata

## Why this exists

A lot of image evaluation workflows are built on idealized or poorly structured data. These datasets are intended to better support:
- AI-image detection evaluation
- image forensics workflows
- robustness testing against screenshot laundering
- transform-aware benchmarking
- dataset inspection before purchase

## Process

The collection workflow includes:
- prompt-driven generation targeting edge cases
- manual review & visual rejection
- deduplication
- physical hardware transform application (Screenshotting/Recompressing)
- precision cropping
- paired dataset construction
- CSV/index generation

## Website / Catalog
** https://safemedia.tech **
