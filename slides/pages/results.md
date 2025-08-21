---
layout: cover
---

# Results

---

```yaml
layout: image-right
image: /figures/2a.jpg
```

# bQTLs

- 49 Individuals of European ancestry
  - Each individual has 1 ChIP-seq dataset from LCL
  - Each individual has genome availabe from 1000 Genomes Project
- 1497 PU.1 bQTLs at FDR <5%
- 250 Null variant sets generated for 1292 bQTL lead variants
- bQTLs are more likely to be associated with blood cell traits compared to
  null variant sets

---

```yaml
layout: image-left
image: /figures/2cd.jpg
```

# Most significant bQTL variants are SNPs

- After colocalization with GWAS blood cell traits, 69 loci significantly alter PU.1 binding
- 51 loci are not structural variants, but are motif altering variants

<v-drag-arrow v-click pos="337,76,-1,199"/>

---

```yaml
layout: image-right
image: /figures/3a.jpg
```

# White blood cell traits

- White blood cell traits are highlighted in yellow
- White blood cell GWAS traits are more common among blood cell traits

---

```yaml
layout: image-right
image: /figures/4b.jpg
```

# QTLs are shared among chromatin signals

- Unshared QTLs may be shared in different cellular contexts

---

```yaml
layout: image-left
image: /figures/5.jpg
```

# bQTLs have less complex signals than eQTLs

<v-clicks>

- eQTLs can have multiple independant variant signals, hiding cell-type specific effects
- bQTLs can reveal these hidden causual variants by using GWAS trait associations
- Claim: ZNF608 expression is controlled by the primary bQTL, not the primary eQTL in causual cell type
  - Lymphocyte count (GWAS) is associated with primary bQTL, not primary eQTL

</v-clicks>

<v-drag pos="248,243,72,40"  >
<div style="font-size: 0.5em; border: 1px solid red; text-align: center;">
primary bQTL
</div>
</v-drag>

<v-drag pos="219,286,72,40"  >
<div style="font-size: 0.5em; border: 1px solid red; text-align: center;">
primary eQTL
</div>
</v-drag>

<v-drag-arrow pos="223,290,-18,-22" width=1px />
<v-drag-arrow pos="254,256,-22,8" width=1px />

<v-drag-arrow v-click pos="336,435,-98,-16" width=1px />

<!-- When we look at B cells, they don't exhibit rs2028854 (lcl primary eQTL) as a primary eQTL -->

---

```yaml
layout: two-cols
```

# MPRA verification of 2 identified variants

- rs5827412 shows reduced reporter activity (negative allelic skew)
- rs3808619 increased reporter activity (positive allelic skew)

::right::

<img src="/figures/6c.jpg" />
<img src="/figures/7f.jpg" />

---

```yaml
layout: image-left
image: /figures/6ab.jpg
```

# Lowered PU.1 binding corresponds to lower monocyte percentage
