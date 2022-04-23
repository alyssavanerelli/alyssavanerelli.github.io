---
layout: page
title: boa mitogenomes
description: Assembling mitochondrial genomes for an entire genus of Caribbean boas
img: assets/img/argentum_pic.jpeg
importance: 3
category: past research
---

This is the research that I completed for my undergraduate thesis at UNC Asheville in the [Reynolds Lab](https://reynoldslab.wp.unca.edu/). 

Read the full paper <i class="fas fa-file"></i> <a class="link" href="{{ '/assets/pdf/thesis_paper.pdf' | prepend: site.baseurl | prepend: site.url }}">here</a>.

***

### Summary of Project

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/argentum_pic.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A Conception Bank Silver Boa (<em>Chilabothrus argentum</em>), the world’s most endangered boa. This adult female is one of only 135 adult animals remaining in the entire species. Photograph by 
R. Graham Reynolds. 
</div>

_Chilabothrus_ is a completely insular genus of boid snakes occurring throughout the West Indies. The genus is composed of 14 species and nearly half of these are newly described or recently
elevated[^1]. Several species within this genus face serious conservation concerns such as introduced predators, anthropogenic habitat destruction, poaching for the pet trade, and low 
genetic diversity[^2],[^3],[^4],[^5]. Two species are listed as endangered on the IUCN Red List, while the newly-discovered _C. argentum_ is critically endangered and represented by as few as 135 
remaining individuals (Figure 1).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/IUCN_fig.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mitogenome_pic.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <b>Figure 1 and 2.</b> <em>Figure 1</em>. IUCN Red List status of the <em>Chilabothrus</em> species analyzed in this study. Made with R. <em>Figure 2</em>. Representative circular mitochondrial 
genome for Chilabothrus snakes.
</div>

Mitochondrial DNA has long been a useful tool in phylogenetic studies[^6], with most studies focusing on sequencing one or two protein-coding regions. Since topologies tend to differ between studies 
using few versus many genes, we generated complete protein-coding mitogenomes for all _Chilabothrus_ species (Figure 2). We used mitochondrial by-catch reads from ultraconserved elements enrichment 
and sequencing to assemble and annotate entire mitogenomes. These mitochondrial genomes are identical in composition and gene order to previously described boid snakes with 13 protein-coding genes, 
22 tRNAs, 2 rRNAs, 2 control regions (CR1 and CR2), and an origin of the light strand replication (Figure 2)[^7].

Sequencing mitogenomes for threatened and endangered species is important in aiding conservation efforts by providing genomic resources. Providing these genetic resources for a threatened genus, 
such as _Chilabothrus_, will provide crucial information that can be used in studies focusing on their evolutionary relationships as well as those investigating population structure and genetic 
diversity. 

We generated a series of protein-coding molecular phylogenies of the entire genus were generated using Bayesian and Maximum Likelihood methods. The maximum-likelihood phylogeny produced a topology 
with strong support at most nodes (Figure 4). In concordance with previous studies[^8], we found that the newly-discovered _C. argentum_ is sister to recently rediscovered _C. schwartzi_ (BS=100; 
Figure 3). The topology shows that _C. exsul_ and _C. strigilatus_ are sister to one another with strong support (BS=99; Figure 3). This differs from previous topological arrangements using only the 
mitochondrial CYTB locus (~1100 bp) showing _C. exsul_ more closely related to _C. striatus_ and the clade containing _C. argentum_ and _C. schwartzi_[^8]. All other relationships agree with 
previously presented phylogenetic analyses. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ML_tree.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <b>Figure 3.</b> Maximum-likelihood phylogeny of 13 <em>Chilabothrus</em> species and 3 species from the genus <em>Boa</em>. Phylogeny was generated using the RAxML 
algorithm in GENEIOUS. Numbers at nodes represent bootstrap support.
</div>

The maximum clade credibility tree produced the same topology as the maximum-likelihood tree (Figure 4). In addition to confirming the relationships among these taxa, this analysis presents 
divergence times of these species. We can use this analysis to estimate times of colonization events from Hispaniola. The first colonization event happened when _C. chrysogaster_ colonized the Turks 
and Caicos around 5 million years ago. The second event happened around 3.5 to 4 million years ago when the clade containing _C. schwartzi_, _C. argentum_, _C. exsul_, and _C. strigilatus_ colonized 
the Bahamas.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCC_tree.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <b>Figure 4.</b> Time-calibrated coalescent tree of aligned concatenated protein-coding loci for all 13 <em>Chilabothrus</em> species. Numbers at nodes represent posterior probabilities times, 
estimated by constraining the root node of <em>Chilabothrus</em> using a normal prior with a mean of 21.7 Mya and a standard deviation of 1.8 Mya. Legend units are million years ago.
</div> 

This is the first study to generate mitogenomes for an entire genus of boas. Being able to easily provide genomic resources for these threatened and endangered boa species is crucial for their 
conservation. Unlike previous studies that used one protein-coding region, the complete protein-coding mitogenomes have given a strongly supported topology for the _Chilabothrus_ phylogeny. Our 
phylogenetic analyses support most previously published relationships of neotropical boids, only differing in topology in terms of the relationships of _C. exsul_, _C. strigilatus_, and _C. 
striatus_.

### References

[^1]: Reynolds RG, Niemiller ML, Hedges SB, Dornburg A, Puente-Rolón AR, Revell LJ. 2013. Molecular phylogeny and historical biogeography of West Indian boid snakes. Mol. 68:461-470.
[^2]: Reynolds RG, Puente-Rolón AR, Geneva AJ, Aviles-Rodriguez KJ, Herrmann NC. 2016. Discovery of a remarkable new boa from the Conception Island Bank, Bahamas. Breviora. 549:1-19.
[^3]: Reynolds RG, Gerber GP. 2012. Ecology and conservation of the Turks Island boa (Epicrates chrysogaster chrysogaster: Squamata: Boidae) on Big Ambergris Cay. J Herpetol. 46(4):578-586.
[^4]: Reynolds RG, Puente-Rolón AR, Platenberg R, Tyler RK, Tolson PJ, Revell LJ. 2015. Large divergence and low diversity suggest genetically informed conservation strategies for the endangered Virgin Islands Boa (Chilabothrus monensis) Glob Ecol Conserv. 3:487-502.
[^5]: Reynolds RG, Henderson RW, Díaz LM, Rodriguez-Cabrera TR, Puente-Rolón AR. In Press. Boas of the West Indies: Evolution, natural history, and conservation. Comstock Publishing Associates, Ithaca, NY.
[^6]: Raposo do Amaral F, Neves LG, Resende MFR, Jr, Mobili F, Miyaki CY, Pellegrino KCM, Biondo C. 2015. Ultraconserved element sequencing as a low-cost source of complete mitochondrial genomes and microsatellite markers in non-model amniotes. PLoS ONE. 10:e0138446.
[^7]: Dong S, Kumazawa Y. 2005. Complete mitochondrial DNA sequences of six snakes: phylogenetic relationships and molecular evolution of genomic features. J Mol Evol. 61:12–22.
[^8]: Reynolds RG, Puente-Rolón AR, Burgess JP, Baker BO. 2018. Rediscovery and a redescription of the Crooked-Acklins boa, Chilabothrus schwartzi (buden, 1975), comb. nov. Breviora. 558:1-16.



