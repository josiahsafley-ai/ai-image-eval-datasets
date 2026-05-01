# AI Image Evaluation Datasets

Curated AI-image evaluation datasets for detection, forensics, and robustness testing.

These datasets are designed around a real-world problem: images rarely stay pristine. In practice, images are often recompressed, screenshotted, re-saved, or passed through messaging and device workflows before they are ever analyzed. Most detection models fail on these edge cases.

👉 **[safemedia.tech](https://safemedia.tech)**

---

## 🎁 Free Download: 75-Image Full-Spectrum Sample Pack
A free sample pack is available so anyone can inspect the exact pipeline and structure before buying. 

We are offering a fully structured, 75-image sample pack generated with Ideogram 3.0. **There are no terms, no restrictions, and no watermarks applied.** Use it freely for your development or evaluation pipelines. 

This pack includes the exact same metadata structure and strict hardware-cropping as our enterprise tiers, spread across all 4 lifecycle transformations:
* Pristine Originals
* Hardware Desktop Screen Captures
* Unsimulated Social Media Recompression
* Physical Mobile Captures

👉 **[Download the Free Sample Pack directly at safemedia.tech](https://safemedia.tech)**

---

## 🔄 The SafeMedia Transformation Pipeline
We provide the 1-to-1 Ground Truth mapping needed to build robust security models across four critical degradation stages:

**1. Pristine Originals:** The raw, unadulterated output straight from the AI generator.
**2. Hardware Desktop Screen Captures:** Images are captured natively on desktop environments via an automated 10-node physical hardware farm to trigger genuine OS-level color-profile shifts and C2PA metadata destruction. 
* *Strict Boundary Cropping:* Our scripts mathematically crop every captured screenshot back to the exact original image borders. There are **zero OS UI elements** (no window frames, no taskbars). Your models are forced to learn sub-pixel degradation without overfitting on desktop backgrounds.
**3. Unsimulated Social Media Recompression:** Manually processed through real-world messaging and social apps to capture native compression artifacts.
**4. Physical Mobile Captures:** True optical laundering captured via real hardware lenses.

---

## 🚨 Latest Update: Unsimulated Social Media Recompression
Our premium vault has just been updated with real-world social media recompression packs. Every degraded image includes a **Pair ID** linking it directly to the pristine original, making it instantly usable for training restoration models, deepfake detectors, and AI watermarking tools.

**The Methodology:**
These aren't simulated degradation scripts. Every single image was manually pushed through actual messaging and social apps to capture real-world compression. To prevent overlapping artifacts and keep your model weights clean, **one image went through only one app**. 

Each dataset contains exactly 1,100 images, processed through:
* Telegram
* Line
* Facebook Messenger (SD & HD)
* WhatsApp (SD & HD)
* Instagram Chat
* X (Posts)

---

## 🧠 Supported Architectures

**Pristine Originals and Hardware Desktop Screen Captures are currently available for ALL models listed below.** ### 🟢 Full Suite Available (Including New Recompression Packs):
* Flux 1.1 Pro Ultra Raw & Flux 2 Pro
* Ideogram 3.0
* GPT 1.5
* Firefly Image 5

### ⏳ Recompression Packs Coming Soon (Originals & Screen Captures Live Now):
* Google Imagen 4
* GPT 2.0
* Midjourney v7 & v8
* Gemini 3.1
* Grok Aurora

---

## 📂 Per-Item Structure & Deliverables

Each item is packaged with structured metadata (including specific `Device_Type` and `OS_Environment` lineage) so the data can be inspected and parsed consistently. 

Each record package contains:
- `target.*` (The image file)
- `metadata.json`

Dataset packs also include:
- Index files (such as `.csv`) for quick ingestion
- README/instruction files
- Transform/grouping information and device hardware lineage in the metadata

---

## 💡 Accessible Pricing
To ensure these datasets are accessible to indie researchers, students, and smaller dev teams, individual packs (1,100 images) across all transformations are available for just **$19.99 each**. 

Plus, to help you build out a robust testing pipeline, you can **mix and match any 4+ packs for an automatic 20% off your total.**

---

## ⚙️ Collection Workflow

Our process ensures rigorous quality control and true physical degradation:
1. Prompt-driven generation targeting edge cases
2. Manual review & visual rejection
3. Deduplication
4. Physical hardware transform application (Screenshotting / Messaging App Recompression)
5. Precision mathematical cropping
6. Paired dataset construction (1-to-1 Ground Truth mappings)
7. CSV/index generation

**Stop training your AI security pipelines on simulated compression. Train them on the real thing.**

**Website / Catalog: https://safemedia.tech**
