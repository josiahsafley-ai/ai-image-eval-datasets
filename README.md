# AI Image Evaluation Datasets

Curated AI-image evaluation datasets for detection, forensics, and robustness testing.

These datasets are designed around a real-world problem: images rarely stay pristine. In practice, images are often recompressed, screenshotted, re-saved, or passed through messaging and device workflows before they are ever analyzed.

https://safemedia.tech

## What the datasets include

The dataset catalog focuses on structured packs built around generators and transforms.

Examples of transform coverage include:
- Original
- Recompressed
- Screenshot
- Desktop Screenshot

Each item is packaged with structured metadata so the data can be inspected and parsed consistently.

## Free sample pack

A free sample pack is available so anyone can inspect the exact structure before buying anything.

The free sample pack:
- includes 75 images
- uses the same general layout as the paid packs
- includes structured metadata
- has no usage restrictions imposed by safemedia.tech

## Paid packs

Single paid packs contain 1,100 images for one generator under one transform.

The free sample pack is intended to demonstrate the same style of packaging and dataset structure used throughout the catalog.

## Per-item structure

Each record package contains:
- `target.*`
- `metadata.json`

Dataset packs may also include:
- index files such as `.csv`
- readme/instruction files
- transform/grouping information in metadata

## Why this exists

A lot of image evaluation workflows are built on idealized or poorly structured data. These datasets are intended to better support:
- AI-image detection evaluation
- image forensics workflows
- robustness testing
- transform-aware benchmarking
- dataset inspection before purchase

## Process

The collection workflow includes:
- prompt-driven generation
- manual review
- deduplication
- transform application
- paired dataset construction
- CSV/index generation

## Website / sample / catalog

Free sample pack and full dataset catalog:

https://safemedia.tech

## Notes

This repository is intended to document the dataset structure and point to the sample/catalog.  
It is not the main distribution point for the paid packs.
