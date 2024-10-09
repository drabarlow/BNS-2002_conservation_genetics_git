---
title       : "Conservation Genetics"
subtitle    : "BNS-2002: Genes, Development, and Evolution"
author      : Dr Axel Barlow
job         : "email: a.barlow@bangor.ac.uk"
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : zenburn      # {zenburn, tomorrow, solarized-dark, ...}
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {selfcontained, standalone, draft}
knit        : slidify::knit2slides
logo        : LA_Full_colour_reversed.svg
biglogo     : A1_FullColour.svg
assets      : {assets: ../../assets}
license     : by-nc-sa

---



<!-- adding bold and italic options -->
<style>
em {
  font-style: italic
}
strong {
  font-weight: bold;
}
</style>

## Lecture schedule

1. Drift and variation (Evolution: Chapter 6)
2. **Conservation genetics (Evolution: Chapter 6)**
3. Phylogeny 1 (Evolution: Chapter 16)
4. Phylogeny 2 (Evolution: Chapter 16)

---

## Genetic drift summary

- Allele frequencies will change from one generation to the next due to chance events
- Such as survival, reproduction, and inheritance.
- Drift is unbiased, no allele is favoured
- **Drift causes a loss of genetic variation** (replaced by mutation or gene flow)
- **Strength of drift is larger in small populations**
- Drift causes populations to become different
- Selection share some features with drift, but alleles are favoured
- Selection is more effective when drift is weak
- We need to account for drift when testing for selection

--- .segue .dark 

## Effective population size

---

## Effective population size (Ne)

**The effective population size (Ne) is the size of an idealised hermaphroditic population that would show the observed amount of drift**

- Loosely, the effective number of breeding individuals

**This is typically different to the census population size**

- Age of reproduction
- Mating systems
- Population structure
- Sex ratio
- Non-random mating

---

## Age of reproduction

<img src="./assets/img/agave.jpg" width="75%" style="display: block; margin: auto;" />

---

## Mating systems

<img src="./assets/img/MacquarieIslandElephantSeal.JPG" width="80%" style="display: block; margin: auto;" />

---

## Population structure

<img src="./assets/img/066-Bridgehampton-NY-06.jpg" width="80%" style="display: block; margin: auto;" />

---

## Sex ratio

<img src="./assets/img/turtle.jpg" width="90%" style="display: block; margin: auto;" />

---

## Non-random mating

<img src="./assets/img/pandas.webp" width="90%" style="display: block; margin: auto;" />

---

## Loss of genetic variation associated with low Ne

<iframe src = 'https://heavywatal.github.io/driftr.js/'></iframe>

--- .segue .dark 

## Why is low genetic variation bad?

--- &twocol

## Smygehuk adders

*** =left

- Population in Sweden
- Low Ne
- Isolated > 100 years
- low genetic diversity
- Population decline
- Many offspring deformed/stillborn

*** =right

<img src="./assets/img/adder_female3.JPG" width="70%" style="display: block; margin: auto;" />

<img src="./assets/img/adder_male2.JPG" width="70%" style="display: block; margin: auto;" />

--- &twocol

## Genetic rescue

*** =left

<img src="./assets/img/adders.svg" width="100%" style="display: block; margin: auto;" />

*** =right

- 20 males from other (large) populations released
- Left for 4 years
- Remaining 8 males returned to source population
- Dramatic increase in recruitment
- Increase in genetic diversity
- Reduction in stillborn offspring

---

## Adders background reading

<embed src="./assets/img/Madsen_adders.pdf" width="100%" height="500" type="application/pdf" />

--- 

## What is going on?

<iframe src = 'https://heavywatal.github.io/driftr.js/'></iframe>

---

## Why is low genetic variation bad?

- At **small population sizes** drift overwhelms the rate of mutation
- In **isolated** populations variation cannot be replaced by gene flow
- Net loss of genetic diversity

### Inbreeding depression

- Deleterious alleles more likely to increase in frequency (selection less effective)
- Deleterious alleles tend to be recessive
- Individuals increasingly homozygous as allele frequency increases (**Hardy-Weinberg**)

### Reduced evolutionary potential

- No variation = no evolution
- Unpredictable because we don't know the future precisely (disease, climate change, etc)

--- 

## Inbreeding depression

<iframe src = 'https://heavywatal.github.io/driftr.js/'></iframe>

--- 

## Reduced evolutionary potential

<iframe src = 'https://heavywatal.github.io/driftr.js/'></iframe>

--- &twocol

## Genetic rescue

*** =left

<img src="./assets/img/adders.svg" width="100%" style="display: block; margin: auto;" />

*** =right

- 20 males from other (large) populations released
- Left for 4 years
- Remaining 8 males returned to source population
- Dramatic increase in recruitment
- Increase in genetic diversity
- Reduction in stillborn offspring

--- .segue .dark 

## Conservation genetics

---

## Conservation genetics

- Applied population genetics to help conserve species

### How can it help?

- **Measure genetic variation**
- **Measure inbreeding**
- Guide breeding programmes
- Identify ancestry
- Wildlife crime

--- &twocol

## Methods: genetic variation

*** =left

**Heterozygosity**

- Measured from a single individual
- How many diploid loci have different alleles
- For example, het sites per kb

**Nuceotide diversity (π)**

- Population average heterozygosity
- Proportion of het positions between 2 randomly selected chromosomes

*** =right

<img src="./assets/img/Gene_Loci_and_Alleles.png" width="75%" style="display: block; margin: auto;" />

---

## Methods: inbreeding

- Chromosome regions are identical by descent
- Can be calculated from pedigrees
- Genome sequencing allows identification of **runs of homozygosity (ROH)**

<img src="./assets/img/recom_roh.svg" width="75%" style="display: block; margin: auto;" />

---

## Methods: runs of homozygosity (ROH)

- Total inbreeding = ROH content
- Recent = long ROH
- Older = short ROH

<img src="assets/fig/unnamed-chunk-13-1.png" width="95%" style="display: block; margin: auto;" />

--- .segue .dark 

## Case studies

--- &twocol

## White rhinos (*Ceratotherium simum*)

*** =left

- Two subspecies: northern and southern
- ~20,000 southern white rhinos (in 2015)
- Northern white rhino functionally extinct (2 females left in 2018)

<img src="./assets/img/rhin_map.svg" width="65%" style="display: block; margin: auto;" />

*** =right

<img src="./assets/img/1920px-Ceratotherium_simum_(21922261908).jpg" width="60%" style="display: block; margin: auto;" />

<img src="./assets/img/rhin_demo.svg" width="75%" style="display: block; margin: auto;" />

---

## White rhinos (*Ceratotherium simum*)

<img src="./assets/img/rhin_res.svg" width="100%" style="display: block; margin: auto;" />

---

## White rhinos background reading

<embed src="./assets/img/Sánchez-Barreiro et al. - 2021 - Historical population declines prompted significant genomic erosion in the northern and southern white.pdf" width="100%" height="500" type="application/pdf" />

--- &twocol

## Pumas (*Puma concolor*)

*** =left

- Puma/cougar/mountain lion/panther
- Widespread across North and South America
- IUCN listed as least concern
- But some populations are small and isolated
- E.g. Florida panther listed as critically endangered
- 8 females introduced from Texas to reduce inbreeding

*** =right

<img src="./assets/img/puma_10.jpg" width="100%" style="display: block; margin: auto;" />

---

## Pumas (*Puma concolor*)

<img src="./assets/img/puma_map.svg" width="100%" style="display: block; margin: auto;" />

---

## Pumas (*Puma concolor*)

<img src="./assets/img/puma_roh.svg" width="100%" style="display: block; margin: auto;" />

---

## Pumas background reading

<embed src="./assets/img/Saremi et al. - 2019 - Puma genomes from North and South America provide insights into the genomic consequences of inbreeding.pdf" width="100%" height="500" type="application/pdf" />

--- &twocol

## Isle Royale wolves

*** =left

- Colonised 2-3 wolves in 1940s
- Expanded to 50 individuals
- Crashed to 14 individuals in 1980s
- Notable improvement 1997 with migration of a single male, followed by second crash
- Moose increased in this period
- 2 wolves left in 2018: father-daughter and half sibs

*** =right

<img src="./assets/img/wolf-isle-royale.jpg" width="85%" style="display: block; margin: auto;" />

<img src="./assets/img/islenpmap.webp" width="85%" style="display: block; margin: auto;" />

---

## Isle Royale wolves

<img src="./assets/img/irwolf.svg" width="90%" style="display: block; margin: auto;" />

--- 

## Wolf reading

<embed src="./assets/img/sciadv.aau0757.pdf" width="100%" height="500" type="application/pdf" />

--- &twocol

## Adders, UK

*** =left

- UK redlist 
- Threatened England
- Near threatened Wales, Scotland
- Large scale declines
- Many pops < 10 adults

*** =right

<img src="./assets/img/adder_female3.JPG" width="70%" style="display: block; margin: auto;" />

<img src="./assets/img/adder_male2.JPG" width="70%" style="display: block; margin: auto;" />

--- bg:white

## Adders, chromosome 6.

<img src="assets/fig/unnamed-chunk-29-1.png" width="100%" style="display: block; margin: auto auto auto 0;" />

--- &thankyou

## Next time:

**Phylogeny 1**
