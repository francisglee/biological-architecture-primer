# Biological Architecture Reading Roadmap

> _I started this reading roadmap focusing on Synthetic Biology, but as I've traveled down the rabbit hole of biological complexity, I realized I was out of my depth. I found myself lost in concepts seemingly unrelated to biology: indexing variation graph, control theory of pattern formation, philosophy of statistics, and hyperparameter tuning for deep neural nets._
>
> _The aim of this document is still the same: documenting papers that are fundamental in designing biological systems. For me, this is a life-long pursuit, as this effort is post-university; there is much to learn, so much to discover. I decided to rename this repository from `synthetic-biology-primers` to `biological-architecture-primer` because a number of these papers do not have `synthetic biology` as a keyword. But they are just as important._

---

If you are a newcomer to the field of Synthetic Biology area, the first question you may have is "What exactly is this convoluted area of hype?", or more importantly, "Which paper should I start reading from?"

There are a few floating definitions of Synthetic Biology, but the [wikedia page](https://en.wikipedia.org/wiki/Synthetic_biology) gives a great one sentance summary that I like the most:

> _Synthetic biology is an interdisciplinary branch of biology and engineering._

Although traditional Synthetic Biology emerged from an electrical engineering perspective of biological systesms, Synthetic Biologists employ techniques from a myriad of academic disciplines. We hope to use Synthetic Biology to understand and design biological processes from biochemical interactions to whole cell organisms, and eventually entire environments and ecosystems.

Our capacity to design biology requires working knowledge of:

- Biology
- Biochemistry
- Biophysics
- Bioinformatics
- Computational Biology
- Systems Biology
- Statistics
- Computer Science
- Control Theory
- Electrical Engineering
- Chemical Engineering
- Ethics and Bioethic
- Manufacturing and Process Engineering
- Data Science and Machine Learning

As so, here you'll find review papers (and some books) in these disciplines as they relate to Synthetic Biology. This roadmap is divided into four categories:

1. Applications of Synthetic Biology
2. Bottom-up approach to biological design
3. Top-down approach to biological interrogation
4. Enabling technologies
5. Cultural impact of Synthetic Biology

You can find select seminal papers (referenced in reviews below) [here](https://github.com/francisglee/synthetic-biology-roadmap/raw/master/seminal-papers.md). I've also listed out the list of resources that go into my RSS feed [here](https://github.com/francisglee/synthetic-biology-roadmap/raw/master/resources.md).

This list is curated by Francis Lee. Please contact me at francis dot g dot lee at gmail dot com for comments and updates!

> //TODO: Explain star metrics.
> //TODO: Create `seminal papers` and `RSS feed` pages.

---

## Table of Contents

1.  [Synthetic Biology Inspirations](#1-synthetic-biology-inspirations)
2.  [History and Future of Synthetic Biology](#2-history-and-future-of-synthetic-biology)
3.  [Microbial Chemical Refineries and Bioproduction](#3-microbial-chemical-refineries-and-bioproduction)
4.  [Mammalian Synthetic Biology](#4-mammalian-synthetic-biology)
5.  [Agriculture and Plant Synthetic Biology](#5-agriculture-and-plant-synthetic-biology)
6.  [Cell-Free Systems](#6-cell-free-systems)
7.  [Ecosystems Engineering](#7-ecosystems-engineering)
8.  [Information Technology](#8-information-technology)
9.  [Parts Design](#9-parts-design)
10. [Synthetic Structural Biology](#10-synthetic-structural-biology)
11. [Gene Circuit Design and Control Theory in Synthetic Biology](#11-gene-circuit-design-and-control-theory-in-synthetic-biology)
12. [Metabolic Engineering and Compartmentalization](#12-metabolic-engineering-and-compartmentalization)
13. [Minimal Genomes and Genome Design](#13-minimal-genomes-and-genome-design)
14. [Bioreactors and the Environment](#14-bioreactors-and-the-environment)
15. [Protocells and Minimal Artificial Organisms](#15-protocells-and-minimal-artificial-organisms)
16. [OMICs Era of Biology](#16-omics-era-of-biology)
17. [Systems Biology](#17-systems-biology)
18. [Whole Cell Modeling](#18-whole-cell-modeling)
19. [Biological Inference and Reverse Engineering Biology](#19-biological-inference-and-reverse-engineering-biology)
20. [Evolution and the Origin of Life](#20-evolution-and-the-origin-of-life)
21. [Nucleotide Technologies](#21-nucleotide-technologies)
22. [Automation and BioProcess Foundries](#22-automation-and-bioprocess-foundries)
23. [Fludics](#23-fluidics)
24. [Imaging and Spectral Tools](#24-imaging-and-spectral-tools)
25. [Computational Methodologies](#25-computational-methodologies)
26. [iGEM and DIYBio](#26-igem-and-diybio)
27. [Synthetic Biology in Industry and the Bioeconomy](#27-synthetic-biology-in-industry-and-the-bioeconomy)
28. [Art, Design, and Fashion](#28-art-design-and-fashion)
29. [Ethics and Bioethics](#29-ethics-and-bioethics)

---

## Introduction

### 1. Synthetic Biology Inspirations

**[1.1]** Woese, Carl R. "**A new biology for a new century.**" Microbiology and molecular biology reviews 68.2 (2004): 173-186. [[pdf]](https://github.com/francisglee/synthetic-biology-roadmap/raw/master/papers/a-new-biology-for-a-new-century-2004.pdf) :star::star::star::star::star:

**[1.2]** Endy, Drew. “**Long Now Synthetic Biology Debate: Drew Endy.**” YouTube, 8 Dec. 2008, Web, 03. Mar. 2017, https://www.youtube.com/watch?v=Fv0hV-gWwGY. :star::star::star::star::star:

**[1.3]** Knight, T. "**Draft Standard for Biobrick Biological Parts**" OpenWetWare RSS. BioBrick Foundation, 3 May 2007. Web. 03 Mar. 2017. [[txt]](https://github.com/francisglee/synthetic-biology-roadmap/raw/master/papers/draft-standard-for-biobrick-biological-parts-2007.txt) :star::star::star::star::star:

**[1.4]** Smith, Eric, and Harold J. Morowitz. "**Universality in intermediary metabolism.**" Proceedings of the National Academy of Sciences 101.36 (2004): 13168-13173. [[link]](./papers/universality-in-intermediate-metabolism-2004.pdf) :star::star::star::star::star:

**[1.5]** Feynman, Richard P., Robert B. Leighton, and Matthew Sands. **The Feynman lectures on physics, Vol. I: The new millennium edition: mainly mechanics, radiation, and heat.** Vol. 1. Basic books, 2011. [[link]](http://www.engineersbench.com/phil/docs/books/The%20Feynman%20Lectures%20on%20Physics%20-%20Book%201.pdf) :star::star::star::star::star:

**[1.6]** Schrodinger, Erwin. **What is Life?: The Physical Aspect of the Living Cell and Mind and Matter; Mind and Matter.** Cambridge University Press, 1967. [[link]](http://www.whatislife.ie/downloads/What-is-Life.pdf) :star::star::star::star::star:

**[1.7]** Pauling, Linus. "**Molecular architecture and biological reactions.**" Chemical and engineering news 24.10 (1946): 1375-1377. [[pdf]](papers/molecular-architecture-and-biological-reactions-1946.pdf) :star::star::star::star::star:

**[1.8]** Lane, Nick. **The Vital Question: Energy, Evolution, and the Origins of Complex Life**. New York City, W. W. Norton & Company; 1 edition, June 21, 2016. [[Amazon]](https://www.amazon.com/Vital-Question-Evolution-Origins-Complex/dp/0393352978/)

### 2. History and Future of Synthetic Biology

**[2.1]** Cameron, D. Ewen, Caleb J. Bashor, and James J. Collins. "**A brief history of synthetic biology.**." Nature Reviews Microbiology. (2014). [[pdf]](https://github.com/francisglee/synthetic-biology-roadmap/raw/master/papers/a-brief-history-of-synthetic-biology-2014.pdf) :star::star::star::star::star:

**[2.2]** George M. Church, Ed Regis. "**Regenesis: How Synthetic Biology Will Reinvent Nature and Ourselves**" Basic Books (2014) [[Amazon]](https://www.amazon.com/Regenesis-Synthetic-Biology-Reinvent-Ourselves/dp/0465075703/ref=pd_sim_14_4?_encoding=UTF8&pd_rd_i=0465075703&pd_rd_r=Q8PFBFCE0HPZR3G54MMA&pd_rd_w=wsimK&pd_rd_wg=SX6cc&psc=1&refRID=Q8PFBFCE0HPZR3G54MMA) :star::star::star::star:

**[2.3]** Roosth, Sophia. "**Synthetic: How Life Got Made.**"" University of Chicago Press, 2017. [[Amazon]](https://www.amazon.com/Synthetic-How-Life-Got-Made/dp/022644046X/ref=sr_1_1?s=books&ie=UTF8&qid=1524092968&sr=1-1&keywords=how+life+got+made) :star::star::star::star::star:

**[2.4]** Kwok, Roberta. "**Five hard truths for synthetic biology: can engineering approaches tame the complexity of living systems? Roberta Kwok explores five challenges for the field and how they might be resolved.**" Nature 463.7279 (2010): 288-291. [[pdf]](https://github.com/francisglee/synthetic-biology-roadmap/raw/master/papers/five-hard-truths-for-synthetic-biology-2010.pdf) :star::star::star::star:

**[2.5]** Ausländer, Simon, David Ausländer, and Martin Fussenegger. "**Synthetic biology—the synthesis of biology.**" Angewandte Chemie International Edition 56.23 (2017): 6396-6419. [[pdf]](./papers/synthetic-biology-the-synthesis-of-biology-2017.pdf)

---

## Applications of Synthetic Biology

### 3. Microbial Chemical Refineries and Bioproduction

#### Drugs and Therapeutics

**[3.1]** Paddon, Chris J., and Jay D. Keasling. "**Semi-synthetic artemisinin: a model for the use of synthetic biology in pharmaceutical development.**" Nature Reviews Microbiology 12.5 (2014): 355. [[pdf]](./papers/semi-synthetic-artemisinin-2014.pdf)

#### Natural Products

**[3.2]** Jullesson, David, et al. "**Impact of synthetic biology and metabolic engineering on industrial production of fine chemicals.**" Biotechnology advances 33.7 (2015): 1395-1402. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/blob/master/papers/impact-of-synthetic-biology-and-metabolic-engineering-on-industrial-production-of-fine-chemicals-2015.pdf) :star::star::star::star::star:

**[3.3]** Smanski, Michael J., et al. "**Synthetic biology to access and expand nature's chemical diversity.**" Nature Reviews Microbiology 14.3 (2016): 135. [[pdf]]()

#### Biomaterials

### 4. Mammalian Synthetic Biology

**[4.1]** Lienert, Florian, et al. "**Synthetic biology in mammalian cells: next generation research tools and therapeutics.**" Nature Reviews Molecular Cell Biology 15.2 (2014): 95-107. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/synthetic-biology-in-mammalian-cells-next-generation-research-tools-and-therapeutics-2014.pdf) :star::star::star::star:

**[4.2]** Ye, Haifeng, Dominique Aubel, and Martin Fussenegger. "**Synthetic mammalian gene circuits for biomedical applications.**" Current opinion in chemical biology 17.6 (2013): 910-917. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/blob/master/papers/synthetic-mammalian-gene-circuits-for-biomedical-applications-2013.pdf) :star::star::star:

**[4.3]** Markson, Joseph S., and Michael B. Elowitz. "**Synthetic biology of multicellular systems: new platforms and applications for animal cells and organisms.**" ACS synthetic biology 3.12 (2014): 875. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/synthetic-biology-of-multicellular-systems-new-platforms-and-applications-for-animal-cells-and-organisms-2014.pdf) :star::star::star::star::

**[4.4]** Esvelt, Kevin M., and Harris H. Wang. "**Genome‐scale engineering for systems and synthetic biology.**" Molecular systems biology 9.1 (2013): 641. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/genome-scale-engineering-for-systems-and-synthetic-biology-2013.pdf) :star::star::star::star::star::

**[4.5]** Esensten, Jonathan H., Jeffrey A. Bluestone, and Wendell A. Lim. "**Engineering therapeutic T cells: from synthetic biology to clinical trials.**" Annual Review of Pathology: Mechanisms of Disease 12 (2017): 305-330.

### 5. Agriculture and Plant Synthetic Biology

**[5.1]** Baltes, Nicholas J., and Daniel F. Voytas. "**Enabling plant synthetic biology through genome engineering.**" Trends in biotechnology 33.2 (2015): 120-131. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/enabling-plant-synthetic-biology-through-genome-engineering-2014.pdf) :star::star::star::star:

**[5.5]** Maurino, Veronica G., and Andreas PM Weber. "**Engineering photosynthesis in plants and synthetic microorganisms.**" Journal of experimental botany 64.3 (2013): 743-751. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/engineering-photosynthesis-in-plants-and-synthetic-microorganisms-2013.pdf) :star::star::star:

**[5.6]** Baltes, Nicholas J., Javier Gil-Humanes, and Daniel F. Voytas. "**Genome engineering and agriculture: opportunities and challenges.**" Progress in molecular biology and translational science. Vol. 149. Academic Press, 2017. 1-26. [[pdf]](./papers/genome-engineering-and-agriculture-opportunities-and-challenges-2017.pdf)

**[5.7]** Llorente, Briardo, Thomas Williams, and Hugh Goold. "**The multiplanetary future of plant synthetic biology.**" Genes 9.7 (2018): 348. [[pdf]](./[papers/the-multiplanetary-future-of-plant-synthetic-biology-2018.pdf)

### 6. Cell-Free Systems

**[6.1]** Pardee, Keith, et al. "**Portable, On-Demand Biomolecular Manufacturing.**" Cell 167 (2016): 248-259. [[pdf]](./papers/portable-on-demand-biomolecular-manufacturing-2016.pdf)

**[6.2]** Karig, David K. "**Cell-free synthetic biology for environmental sensing and remediation.**" Current opinion in biotechnology 45 (2017): 69-75. [[pdf]](./papers/Cell-free synthetic biology for environmental sensing and remediation.pdf)

### 7. Ecosystems Engineering

**[7.1]** Mueller, U. G., and J. L. Sachs. "**Engineering microbiomes to improve plant and animal health.**" Trends in microbiology 23.10 (2015): 606-617. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/engineering-microbiomes-to-improve-plant-and-animal-health-2015.pdf) :star::star::star:

**[7.2]** Esvelt, Kevin M., et al. "**Concerning RNA-guided gene drives for the alteration of wild populations.**" Elife 3 (2014): e03401. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/emerging-technology-concerning-rna-guided-gene-drives-for-the-alteration-of-wild-populations-2014.pdf) :star::star::star:

**[7.3]** Brenner, Katie, Lingchong You, and Frances H. Arnold. "**Engineering microbial consortia: a new frontier in synthetic biology.**" Trends in biotechnology 26.9 (2008): 483-489. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/engineering-microbial-consortia-a-new-frontier-in-synthetic-biology-2008.pdf) :star::star::star::star::star:

### 8. Information Technology

**[8.1]** Yazdi, SM Hossein Tabatabaei, Ryan Gabrys, and Olgica Milenkovic. "**Portable and error-free DNA-based data storage.**" Scientific reports 7.1 (2017): 5011. [[pdf]](./papers/portable-and-error-free-dna-based-data-storage-2017.pdf)

**[8.2]** Organick, Lee, et al. "**Random access in large-scale DNA data storage.**" Nature biotechnology 36.3 (2018): 242. [[pdf]](./papers/random-access-in-large-scale-dna-data-storage-2018.pdf)

---

## Bottom-up Approach to Biological Design

### 9. Parts Design

**[]** DNA Design

**[]** Isaacs, Farren J., Daniel J. Dwyer, and James J. Collins. "**RNA synthetic biology.**" Nature biotechnology 24.5 (2006): 545-554. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/rna-synthetic-biology-2006.pdf) :star::star::star::star::star:

**[]** McKeague, Maureen, Remus S. Wong, and Christina D. Smolke. "**Opportunities in the design and application of RNA for gene expression control.**" Nucleic acids research (2016): gkw151. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/opportunities-in-the-design-and-application-of-rna-for-gene-control-expression-2016.pdf) :star::star::star:

**[]** Protein Design

**[]** Packer, Michael S., and David R. Liu. "**Methods for the directed evolution of proteins.**" Nature Reviews Genetics 16.7 (2015): 379-394. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/methods-for-the-directed-evolution-of-proteins-2015.pdf) :star::star::star::star:

### 10. Synthetic Structural Biology

**[10.1]** Keung, Albert J., et al. "**Chromatin regulation at the frontier of synthetic biology.**" Nature Reviews Genetics 16.3 (2015): 159-171. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/chromatin-regulation-at-the-frontier-of-synthetic-biology-2015.pdf) :star::star::star::star:

**[]** DNA architecture

### 11. Gene Circuit Design and Control Theory in Synthetic Biology

**[11.1]** Brophy, Jennifer AN, and Christopher A. Voigt. "**Principles of genetic circuit design.**" Nature methods 11.5 (2014): 508-520. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/principles-of-genetic-circuit-design-2014.pdf)) :star::star::star::star::star:

**[11.2]** Qian, Yili, Cameron McBride, and Domitilla Del Vecchio. "**Programming cells to work for us.**" Annual Review of Control, Robotics, and Autonomous Systems 1 (2018): 411-440. [[pdf]](./papers/programming-cells-to-work-for-us-2018.pdf) :star::star::star::star::star:

### 12. Metabolic Engineering and Compartmentalization

**[12.1]** Woolston, Benjamin M., Steven Edgar, and Gregory Stephanopoulos. "**Metabolic engineering: past and future.**" Annual review of chemical and biomolecular engineering 4 (2013): 259-288. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/metabolic-engineering-past-and-future-2013.pdf) :star::star::star::star:

**[12.3]** Boyle, Patrick M., and Pamela A. Silver. "**Parts plus pipes: synthetic biology approaches to metabolic engineering.**" Metabolic engineering 14.3 (2012): 223-232. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/fa806c8fc908d6dc77bdf8bcb18c15fab5e55cae/papers/parts-plus-pipes-synthetic-biology-approaches-to-metabolic-engineering-2011.pdf) :star::star::star::star:

**[]** Energetics and resource sharing

### 13. Minimal Genomes and Genome Design

**[13.1]** Mushegian, Arcady. "**The minimal genome concept.**" Current opinion in genetics & development 9.6 (1999): 709-714. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/blob/master/papers/the-minimal-genome-concept-1999.pdf) :star::star::star::star::star:

**[13.2]** Hutchison, Clyde A., et al. "**Design and synthesis of a minimal bacterial genome.**" Science 351.6280 (2016): aad6253. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/design-and-synthesis-of-a-minimal-bacterial-genome-2016.pdf) :star::star::star::star::star:

> This is not a review.

**[13.3]** Haimovich, Adrian D., Paul Muir, and Farren J. Isaacs. "**Genomes by design.**" Nature Reviews Genetics 16.9 (2015): 501-516. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/genomes-by-design-2015.pdf) :star::star::star:

### 14. Bioreactors and the Environment

### 15. Protocells and Minimal Artificial Organisms

**[15.1]** Adamala, Katarzyna P., et al. "**Engineering genetic circuit interactions within and between synthetic minimal cells.**" Nature chemistry 9.5 (2017): 431. [[pdf]](./papers/engineering-genetic-circuit-interactions-within-and-between-synthetic-minimal-cells-2016.pdf)

**[15.2]** Yewdall, N. Amy, Alexander F. Mason, and Jan CM van Hest. "**The hallmarks of living systems: towards creating artificial cells.**" Interface Focus 8.5 (2018): 20180023. [[pdf]](./papers/the-hallmarks-of-living-systems-towards-creating-artificial-cells-2018.pdf)

---

## Top-down Approach to Biological Interrogation

### 16. OMICs Era of Biology

### 17. Systems Biology

**[17.1]** Nielsen, Jens. "**Systems biology of metabolism.**" Annual review of biochemistry 86 (2017): 245-275. [[pdf]](./papers/systems-biology-of-metabolism-2017.pdf)

**[17.2]** Tavassoly, Iman, Joseph Goldfarb, and Ravi Iyengar. "**Systems biology primer: the basic methods and approaches.**" Essays in biochemistry 62.4 (2018): 487-500. [[pdf]](./papers/systems-biology-primer-2018)

**[17.3]** Wu, Gang, et al. "**Metabolic burden: cornerstones in synthetic biology and metabolic engineering applications.**" Trends in biotechnology 34.8 (2016): 652-664. [[pdf]](./papers/metabolic-burden-2016.pdf)

**[17.4]** Orth, Jeffrey D., Ines Thiele, and Bernhard Ø. Palsson. "**What is flux balance analysis?**" Nature biotechnology 28.3 (2010): 245-248. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/what-is-flux-balance-analysis-2010.pdf) :star::star::star::star::star:

**[]** Energetics and Resource Sharing

### 18. Whole Cell Modeling

**[18.1]** Macklin, Derek N., Nicholas A. Ruggero, and Markus W. Covert. "**The future of whole-cell modeling.**" Current opinion in biotechnology 28 (2014): 111-115. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/the-future-of-whole-cell-modeling-2014.pdf) :star::star::star:

### 19. Biological Inference and Reverse Engineering of Biology

### 20. Evolution and the Origin of Life

**[]** Kacar, Betul, and Eric Gaucher. "**Towards the recapitulation of ancient history in the laboratory: combining synthetic biology with experimental evolution.**" arXiv preprint arXiv:1209.5032 (2012). [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/towards-the-recapitulation-of-ancient-history-in-the-laboratory-combining-synthetic-biology-with-experimental-evolution-2014.pdf) :star::star:

**[]** Bayer, Travis S. "**Using synthetic biology to understand the evolution of gene expression.**" Current Biology 20.17 (2010): R772-R779. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/using-synthetic-biology-to-understand-the-evolution-of-gene-expression-2010.pdf) :star::star:

---

## Enabling Technologiees

### 21. Nucleotide Technologies

#### Sequencing

**[21.1]** Mardis, Elaine R. "**DNA sequencing technologies: 2006-2016.**" Nature Protocols 12.2 (2017): 213-218. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/dna-sequencing-technologies-2006-2016-2017.pdf) :star::star::star:

#### DNA Synthesis and Assembly

**[21.2]** Kosuri, Sriram, and George M. Church. "**Large-scale de novo DNA synthesis: technologies and applications.**" Nature methods 11.5 (2014): 499-507. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/large-scale-de-novo-dna-synthesis-technologies-and-applications-2014.pdf) :star::star::star::star:

**[21.3]** Chao, Ran, Yongbo Yuan, and Huimin Zhao. "**Recent advances in DNA assembly technologies.**" FEMS yeast research 15.1 (2015): 1-9. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/recent-advances-in-dna-assembly-technologies-2015.pdf) :star::star::star:

**[21.4]** Casini, Arturo, et al. "**Bricks and blueprints: methods and standards for DNA assembly.**" Nature Reviews Molecular Cell Biology 16.9 (2015): 568. [[pdf]](./papers/bricks-and-blueprints-2015.pdf)

#### Nucleotide Editing

**[21.5]** Knott, Gavin J., and Jennifer A. Doudna. "**CRISPR-Cas guides the future of genetic engineering.**" Science 361.6405 (2018): 866-869. [[pdf]](./papers/crispr-cas-guides-the-future-of-genetic-engineering)

**[21.6]** Hess, Gaelen T., et al. "**Methods and applications of CRISPR-mediated base editing in eukaryotic genomes.**" Molecular cell 68.1 (2017): 26-43. [[pdf]](methods-and-applications-of-crispr-mediated-base-editing-in-eukaryotic-genomes-2017.pdf)

#### Delivery Technologies

**[21.7]** Jahangirian, Hossein, et al. "**A review of drug delivery systems based on nanotechnology and green chemistry: green nanomedicine.**" International journal of nanomedicine 12 (2017): 2957. [[pdf]](./papers/a-review-of-drug-delivery-systems-based-on-nanotechnology-and-green-chemistry-2017.pdf)

**[21.8]** Yin, Hao, Kevin J. Kauffman, and Daniel G. Anderson. "**Delivery technologies for genome editing.**" Nature reviews Drug discovery 16.6 (2017): 387. [[pdf]](./papers/delivery-technologies-for-genome-editing-2017.pdf)

### 22. Automation and BioProcess Foundries

**[22.1]** Boles, Kent S., et al. "**Digital-to-biological converter for on-demand production of biologics.**" Nature biotechnology 35.7 (2017): 672. [[pdf]](./papers/digital-to-biological-converter-for-on-demand-production-of-biologics-2018.pdf)

**[22.2]** Chao, Ran, et al. "**Engineering biological systems using automated biofoundries.**" Metabolic engineering 42 (2017): 98-108.

### 23. Fluidics

#### Macrofluidics

**[]** Bioprocess Bioreactors

**[]** Tissue Bioreactors

#### Microfluidics

**[]** Lab on a Chip

**[]** Droplet Manipulation

#### uTAS

**[]** Patabadige, Damith EW, et al. "**Micro total analysis systems: fundamental advances and applications.**" Analytical chemistry 88.1 (2015): 320-338. [[pdf]](./papers/https://pubs.acs.org/doi/abs/10.1021/acs.analchem.5b04310?journalCode=ancham)

### 24. Imaging and Spectral Tools

### 25. Computational Methodologies

#### Mathematical

#### Algorithmic

#### Stastistical

#### Machine Learning

**[]** Camacho, Diogo M., et al. "**Next-generation machine learning for biological networks.**" Cell (2018). [[pdf]](./papers/next-generation-machine-learning-for-biological-networks-2018.pdf)

#### Intuition

**[]** Raue, Andreas, et al. "**Lessons learned from quantitative dynamical modeling in systems biology.**" PLoS One 8.9 (2013): e74335. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/lessons-learned-from-quantitative-dynamical-modeling-in-systems-biology-2013.pdf) :star::star::star::star::star:

**[]** Gunawardena, Jeremy. "**Models in biology:‘accurate descriptions of our pathetic thinking’.**" BMC biology 12.1 (2014): 29. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/models-in-biology-accurate-descriptions-of-our-pathetic-thinking-2014.pdf) :star::star::star::star:

---

## Cultural Impact of Synthetic Biology

### 26. iGEM and DIYBio

**[26.1]** Matheson, Susan. "**Engineering a Biological Revolution.**" Cell 168.3 (2017): 329-332. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/engineering-a-biological-revolution-2017.pdf) :star::star::star:

**[26.2]** Brown, James. "**The iGEM competition: building with biology.**" IET Synthetic Biology 1.1 (2007): 3-6. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/the-igem-competition-building-with-biology-2007.pdf) :star::star::star::star:

### 27. Synthetic Biology in Industry and the Bioeconomy

**[27.1]** SynBioBeta [[link]](http://synbiobeta.com/)

**[27.2]** IndieBio [[link]](http://indiebio.co/)

**[27.3]** Bergin J. "**Synthetic Biology: Global Markets**” BBC Research. 2017. Web. 3 Mar. 2014. [[pdf]](https://github.com/crimsonigem/synthetic-biology-reading-roadmap/raw/master/papers/synthetic-biology-global-markets-2017.pdf) :star::star::star:

**[27.4]** Dietz, Thomas, et al. "**Governance of the bioeconomy: A global comparative study of national bioeconomy strategies.**" Sustainability 10.9 (2018): 3190. [[pdf]](./papers/governance-of-the-bioeconomy-2018.pdf)

**[27.5]** Zilberman, David, et al. "**Economics of Sustainable Development and the Bioeconomy.**" Applied Economic Perspectives and Policy 40.1 (2018): 22-37. [[pdf]](./papers/economics-of-sustainable-development-and-the-bioeconomy-2018.pdf)

### 28. Art, Design, and Fashion

**[28.1]** Agapakis, Christina M. "**Designing synthetic biology.**" ACS synthetic biology 3.3 (2013): 121-128. [[pdf]](https://github.com/crimsonigem/synthetic-biology-reading-roadmap/raw/master/papers/designing-synthetic-biology-2013.pdf) :star::star:

**[28.2]** Oxman, Neri. "**Templating Design for Biology and Biology for Design.\***" Architectural Design 85.5 (2015): 100-107. [[pdf]](https://github.com/crimsonigem/synthetic-biology-reading-roadmap/raw/master/papers/templating-design-for-biology-and-biology-for-design-2015.pdf) :star::star::star:

**[28.3]** Dance, Amber. "**Science and Culture: The art of designing life.**" Proceedings of the National Academy of Sciences 112.49 (2015): 14999-15001. [[pdf]](https://github.com/crimsonigem/synthetic-biology-reading-roadmap/raw/master/papers/science-and-culture-the-art-of-designing-life-2015.pdf) :star::star::star:

**[28.4]** Descience [[link]](http://www.fashiondescience.com/)

**[28.5]** BioFabricate [[link]](http://www.biofabricate.co/)

### 29. Ethics and Biosafety

**[29.1]** Barras, Vincent, and Gilbert Greub. "**History of biological warfare and bioterrorism.**" Clinical Microbiology and Infection 20.6 (2014): 497-502. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/history-of-biological-warfare-and-bioterrorism-2014.pdf) :star::star::star:

**[29.2]** Douglas, Thomas, and Julian Savulescu. "**Synthetic biology and the ethics of knowledge.**" Journal of medical ethics 36.11 (2010): 687-693. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/synthetic-biology-and-the-ethics-of-knowledge-2010.pdf) :star::star::star:

**[29.3]** Gutmann, Amy. "**The ethics of synthetic biology: guiding principles for emerging technologies.**" Hastings Center Report 41.4 (2011): 17-22. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/the-ethics-of-synthetic-biology-guiding-principles-for-emerging-technologies-2011.pdf) :star::star::star:

**[29.4]** Redford, Kent H., William Adams, and Georgina M. Mace. "**Synthetic biology and conservation of nature: wicked problems and wicked solutions.**" PLoS Biol 11.4 (2013): e1001530. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/synthetic-biology-and-conservation-of-nature-wicked-problems-and-wicked-solutions-2013.pdf) :star::star::star:

**[29.5]** Oye, Kenneth A., et al. "**Regulating gene drives.**" Science 345.6197 (2014): 626-628. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/regulating-gene-drives-2014.pdf) :star::star::star::star:

https://plato.stanford.edu/entries/systems-synthetic-biology/

---
