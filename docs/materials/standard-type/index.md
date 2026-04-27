# Materials by standard type

[← Materials (section index)](../index.md)

This area groups the knowledge base by **standard family** (DIN, ISO, GB/T, ASTM, JIS, and others). You can return to the [section map](../index.md#section-map) from the [Materials index](../index.md) at any time.

## On each page

1. `## Overview` for the family.
2. One or more `##` material blocks (`##` title = designator, then five fields: **Alias** … **Standard Source**).
3. For each block: `### Chemical composition` and `### Mechanical property` in that order, with horizontal rules as in the [layout template](template.md).

## Categories (A–Z)

- [Unspecified or mixed](./category-01.md)
- [AS](./as.md)
- [ASTM](./astm.md)
- [BS](./bs.md)
- [CNS](./cns.md)
- [DIN](./din.md)
- [DIN EN ISO](./din-en-iso.md)
- [EN](./en.md)
- [GB/T](./gb-t.md)
- [GJB](./gjb.md)
- [GJB/美国](./gjb-2.md)
- [GOST](./gost.md)
- [HB](./hb.md)
- [ISO](./iso.md)
- [JIS](./jis.md)
- [KS](./ks.md)
- [QIB](./qib.md)
- [SAE](./sae.md)
- [TB](./tb.md)
- [YB](./yb.md)

### For maintainers (internal)

To refresh the category list and blank shells from the internal material database: `python3 scripts/query_fchem_material.py --generate-docs`, then commit. Hand-curated pages (e.g. [DIN](./din.md) examples) are protected and not overwritten.
