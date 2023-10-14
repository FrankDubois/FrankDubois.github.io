---
layout: page
title: Essential regulatory elements of high-level amplicons as cancer type specific growth dependencies
description: Max-Eder Project 
img: assets/img/DKH_Logo_s.jpg
importance: 1
category: lab
related_publications: 
---

Most cancer genomes experience DNA amplifications as the most common gain-of-function alterations leading to overexpression of oncogenes. 

Why does this work? 
How does the transcriptional regulation of the oncogenes get hijacked on these amplifications? 
Do they exploit tissue-specific enhancers and transcription factors for oncogene expression and cancer growth? 

We combine whole genome sequencing of hundreds of breast and lung cancers including long-read and epigenetic analyses with validation of our findings using CRISPR-based genome engineering to answer these questions. 

Understanding which regulatory factors are essential for cancer growth could lead to novel tissue-specific gene regulation targeting therapies.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ecDNA_FISH.jpg" title="ecDNA FISH" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Metaphase FISH image of cells with normal karyotype (left) and brain cancer cells with a high-level amplicon of MYCN and ID2 on extrachromosomal DNA (right) – a phenomenon only observed in malignant cells. (image from Dubois F et al. Nature Cancer. 2022.) 
</div>
The coding sequences of the oncogenes are only a small fraction of the amplified DNA. Why are the cancer cells keeping 50+ copies of the rest? Are there essential regulatory elements in these co-amplified regions?
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MYCN_ID2ecDNARec.jpg" title="MYCN-ID2 ecDNA" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Reconstruction of an MYCN-ID2 extrachromosomal DNA (ecDNA) amplicon. The plot shows two loci on chromosome 2 with the positions of the coding sequences of the MYCN and ID2 genes highlighted in blue and orange respectively. The larger red boxes show co-amplified regions that could contain essential regulatory elements. (from Dubois F et al. Nature Cancer. 2022.) 
</div>

To answer these questions we will analyze a several hundert breast and lung cancer tumor samples by whole genome sequencing including with long-read technology.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:
