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

<v-clicks>

- 49 Individuals of European ancestry
  - Each individual has ChIP-seq dataset from LCL
  - Each individual has genotype data available from 1000 Genomes Project
- 1497 PU.1 bQTLs at FDR <5%
- 250 Null variant sets generated for 1292 bQTL lead variants (SNPsnap)
- bQTLs are more likely to be associated with blood cell traits compared to
  null variant sets

</v-clicks>

---

```yaml
layout: image-left
image: /figures/2cd.jpg
```

# Most significant bQTL variants are SNPs

- GWAS associations are from UK biobank
- After colocalization with GWAS blood cell traits, 69 loci significantly alter PU.1 binding
- 51 loci are not structural variants, but are motif altering variants

<v-clicks>

- PU.1 forms complex with IRF resulting in an altered binding schema called a composite motif
- SNPs are "normally" distributed along both motifs

</v-clicks>

<v-drag-arrow v-click pos="337,76,-1,199"/>

---

```yaml
layout: image-right
image: /figures/3a.jpg
```

# White blood cell traits

- White blood cell traits are highlighted in yellow
- White blood cell GWAS traits are more common among blood cell traits colocalized
  with bQTLs

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

- eQTLs can have multiple independent variant signals, hiding cell-type specific effects
- Claim: ZNF608 expression is controlled by the primary bQTL, not the primary eQTL in causal cell type
  - Lymphocyte count (GWAS) is associated with primary bQTL, not primary eQTL
  - primary eQTL does not alter PU.1 binding
  - B cells only have secondary eQTL

</v-clicks>

<v-drag pos="244,238,78,40"  >
<div style="font-size: 0.5em; border: 1px solid red; text-align: center;">
primary bQTL/secondary eQTL
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

<!--
When we look at B cells, they don't exhibit rs2028854 (lcl primary eQTL) as a primary eQTL
-->

---

```yaml
layout: two-cols
```

# MPRA verification of rs5827412

- rs5827412 is a short deletion removing a section of the PU.1 motif
- rs5827412 shows reduced reporter activity (negative allelic skew)
- reporter activity is used as a proxy for "regulatory activity"
- decreased regulatory activity is consistent with lowered PU.1 binding

::right::

<img src="/figures/6b.jpg" />
<img src="/figures/6c.jpg" />

---

```yaml
layout: image-right
image: /figures/6defg.jpg
```

# SPI1 knockout leads to lowered chromatin accessibility at LRRC25

- rs5827412 is in the LRRC25 locus
- LRRC25 is expressed throughout monocyte differentiation (E)

<v-drag-arrow  v-click color="red" pos="642,253,96,-16"/>

<v-drag-arrow v-click="+2" pos="635,518,107,-88"/>
<v-drag-arrow v-click="+2" pos="597,308,145,-40"/>

---

```yaml
layout: two-cols
```

# MPRA verification of rs3808619

- rs3808619 increased reporter activity (positive allelic skew)
- increases regulatory activity consistent with heightened PU.1 binding

::right::

<img src="/figures/7a.jpg" />
<img src="/figures/7f.jpg" />

---

```yaml
layout: image-right
image: /figures/7g.jpg
```

# SPI1 knockout leads to reduced accessibility at ZC2HC1A promoter

- rs3808619 is located in ZC2HC1A promoter
- chromatin accessibility is altered at this region when SPI1 is knocked out
