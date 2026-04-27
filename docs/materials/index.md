# Materials

The **materials** section is separate from the [standards](../standards/index.md) list: here we describe **base materials, grades, and the datasheet model** we use in technical and commercial documents.

## Section map

| Layer | What it is | Where to go |
|--------|------------|-------------|
| **Topic guides** | Cross-cutting topics (e.g. carbon vs stainless) | [Topic guides](#topic-guides) |
| **By standard type** | One page per **standard family** in our material catalog (DIN, ISO, GB/T, …) | [By standard type (index)](./standard-type/index.md) |
| **Layout (reference)** | One-page blank template: title, metadata, two tables | [Material datasheet template](./standard-type/template.md) |

## Topic guides

- [Carbon steel vs stainless steel](./carbon-steel-vs-stainless-steel.md)

## By standard type (categories)

Classified by **Standard Type** (e.g. DIN, ISO, GB/T). Most pages are **empty shells** until you add grades. **DIN** has filled examples: [DIN (examples)](./standard-type/din.md).

- [Full index: all standard types (A–Z)](./standard-type/index.md)

## How a category page is built

Use the [template](standard-type/template.md) as the single source for **field order** and **headings**. Every `standard-type/*.md` file follows the same idea:

1. `#` **Category title** (the standard family)
2. `## Overview`
3. One or more **materials**, each with `##` = **grade / designation**
4. Under each `##` material: five lines (**Alias** … **Standard Source**), then `---`, then `### Chemical composition`, `### Mechanical property`

See a filled pair of examples in [DIN](./standard-type/din.md). Other families link from [the standard-type index](standard-type/index.md).

## EternalFast

Wuxi EternalFast Metal Co., Ltd. provides material recommendations and full traceability documentation for global projects.  
Website: [https://eternalfast.com](https://eternalfast.com)
