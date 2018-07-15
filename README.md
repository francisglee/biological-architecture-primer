# Synthetic Biology Papers Reading Roadmap

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

As so, here you'll find review papers (and some books) in these disciplines as they relate to Synthetic Biology. You can find select seminal papers (referenced in reviews below) [here](https://github.com/francisglee/synthetic-biology-primers/blob/master/seminal-papers.md). I've also listed out the list of resources that go into my RSS feed [here](https://github.com/francisglee/synthetic-biology-primers/blob/master/resources.md).

This list is curated by Francis Lee. Please contact me at francis dot g dot lee at gmail dot com for comments and updates!

> //TODO: Explain star metrics.

---

## Table of Contents

1.  [Synthetic Biology Inspirations](#1-synthetic-biology-inspirations)
2.  [History and Future of Synthetic Biology](#2-history-and-future-of-synthetic-biology)
3.  [Gene Circuit and Modeling in Synthetic Biology](#3-gene-circuit-and-modeling-in-synthetic-biology)
4.  [Metabolic Engineering and Compartmentalization](#4-metabolic-engineering-and-compartmentializatn)
5.  [Minimal Genome and Genome Design](#5-minimal-genome-and-genome-design)
6.  [Whole Cell Modeling](#6-whole-cell-modeling)
7.  [Intuition in Mathematical and Systems Biology](#7-intuition-in-mathematical-and-systems-biology)
8.  [Environments and the Bioreactor](#8-environment-and-the-bioreactor)
9.  [Ecosystems Engineering](#9-ecosystems-engineering)
10. [Microbial Chemical Refineries](#10-microbial-chemical-refinery)
11. [Mammalian Synthetic Biology](#11-mammalian-synthetic-biology)
12. [Plant Synthetic Biology and Photosynthesis](#12-plant-synthetic-biology-and-photosynthesis)
13. [Biomaterials and Bioarchitecture](#13-biomaterials-and-bioarchitecture)
14. [Cell-Free Systems](#14-cell-free-systems)
15. [DNA Sequencing and Synthesis](#15-dna-sequencing-and-synthesis)
16. [Synthetic Biology and Evolution](#16-synthetic-biology-and-evolution)
17. [RNA Synthetic Biology](#17-rna-synthetic-biology)
18. [DNA Editing](#18-dna-editing)
19. [OMICs Era of Biology](#19-omics-era-of-biology)
20. [Biological Inference and Reverse Engineering Biology](#20-biological-inference-and-reverse-engineering-biology)
21. [Computational Design of Biological Systems](#21-computational-design-of-biological-systems)
22. [iGEM and DIYBio](#22-igem-and-diybio)
23. [Synthetic Biology in Industry](#23-synthetic-biology-in-industry)
24. [Art, Design, and Fashion](#24-art-design-and-fashion)
25. [Ethics and Bioethics](#25-ethics-and-bioethics)

---

## 1. Synthetic Biology Inspirations

**[1.1]** Woese, Carl R. "**A new biology for a new century.**" Microbiology and molecular biology reviews 68.2 (2004): 173-186. [[pdf]](https://github.com/francisglee/synthetic-biology-roadmap/raw/master/papers/a-new-biology-for-a-new-century-2004.pdf) :star::star::star::star::star:

**[1.2]** Endy, Drew. “**Long Now Synthetic Biology Debate: Drew Endy.**” YouTube, 8 Dec. 2008, Web, 03. Mar. 2017, https://www.youtube.com/watch?v=Fv0hV-gWwGY. :star::star::star::star::star:

**[1.3]** Knight, T. "**Draft Standard for Biobrick Biological Parts**" OpenWetWare RSS. BioBrick Foundation, 3 May 2007. Web. 03 Mar. 2017. [[txt]](https://github.com/francisglee/synthetic-biology-roadmap/raw/master/papers/draft-standard-for-biobrick-biological-parts-2007.txt) :star::star::star::star::star:

**[]** morowitz  
**[]** feynman  
**[]** lac operon  
**[]** restriction enzymes  
**[]** Discovery of DNA  

---

## 2. History and Future of Synthetic Biology

**[2.1]** Cameron, D. Ewen, Caleb J. Bashor, and James J. Collins. "**A brief history of synthetic biology.**." Nature Reviews Microbiology. (2014). [[pdf]](https://github.com/francisglee/synthetic-biology-roadmap/raw/master/papers/a-brief-history-of-synthetic-biology-2014.pdf) :star::star::star::star::star:

**[2.2]** George M. Church, Ed Regis. "**Regenesis: How Synthetic Biology Will Reinvent Nature and Ourselves**" Basic Books (2014) [[Amazon]](https://www.amazon.com/Regenesis-Synthetic-Biology-Reinvent-Ourselves/dp/0465075703/ref=pd_sim_14_4?_encoding=UTF8&pd_rd_i=0465075703&pd_rd_r=Q8PFBFCE0HPZR3G54MMA&pd_rd_w=wsimK&pd_rd_wg=SX6cc&psc=1&refRID=Q8PFBFCE0HPZR3G54MMA) :star::star::star::star:

**[2.3]** Roosth, Sophia. "**Synthetic: How Life Got Made.**"" University of Chicago Press, 2017. [[Amazon]](https://www.amazon.com/Synthetic-How-Life-Got-Made/dp/022644046X/ref=sr_1_1?s=books&ie=UTF8&qid=1524092968&sr=1-1&keywords=how+life+got+made) :star::star::star::star::star:

**[2.4]** Kwok, Roberta. "**Five hard truths for synthetic biology: can engineering approaches tame the complexity of living systems? Roberta Kwok explores five challenges for the field and how they might be resolved.**" Nature 463.7279 (2010): 288-291. [[pdf]](https://github.com/francisglee/synthetic-biology-roadmap/raw/master/papers/five-hard-truths-for-synthetic-biology-2010.pdf) :star::star::star::star:

**[2.5]** Way, Jeffrey C., et al. "**Integrating biological redesign: where synthetic biology came from and where it needs to go.**" Cell 157.1 (2014): 151-161. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/integrating-biological-redesign-where-synthetic-biology-came-from-and-where-it-needs-to-go-2014.pdf) :star::star::star::star:

---

## 3. Gene Circuit Design and Modeling in Synthetic Biology

**[3.1]** Brophy, Jennifer AN, and Christopher A. Voigt. "**Principles of genetic circuit design.**" Nature methods 11.5 (2014): 508-520. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/principles-of-genetic-circuit-design-2014.pdf))
:star::star::star::star::star:

**[3.2]** Slusarczyk, Adrian L., Allen Lin, and Ron Weiss. "**Foundations for the design and implementation of synthetic genetic circuits.**" Nature Reviews Genetics 13.6 (2012): 406-420. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/foundations-for-the-design-and-implementation-of-synthetic-genetic-circuits-2012.pdf) :star::star::star::star::star:

**[3.3]** Wall, Michael E., William S. Hlavacek, and Michael A. Savageau. "**Design of gene circuits: lessons from bacteria.**" Nature Reviews Genetics 5.1 (2004): 34-42. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/design-of-gene-circuits-lessions-from-bacteria-2004.pdf) :star::star::star::star::star:

---

## 4. Metabolic Engineering and Compartmentalization

**[4.1]** Woolston, Benjamin M., Steven Edgar, and Gregory Stephanopoulos. "**Metabolic engineering: past and future.**" Annual review of chemical and biomolecular engineering 4 (2013): 259-288. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/metabolic-engineering-past-and-future-2013.pdf) :star::star::star::star:

**[4.2]** Orth, Jeffrey D., Ines Thiele, and Bernhard Ø. Palsson. "**What is flux balance analysis?**" Nature biotechnology 28.3 (2010): 245-248. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/what-is-flux-balance-analysis-2010.pdf) :star::star::star::star::star:

**[4.3]** Boyle, Patrick M., and Pamela A. Silver. "**Parts plus pipes: synthetic biology approaches to metabolic engineering.**" Metabolic engineering 14.3 (2012): 223-232. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/fa806c8fc908d6dc77bdf8bcb18c15fab5e55cae/papers/parts-plus-pipes-synthetic-biology-approaches-to-metabolic-engineering-2011.pdf) :star::star::star::star:

---

## 5. The Minimal Genome and Genome Design

**[5.1]** Mushegian, Arcady. "**The minimal genome concept.**" Current opinion in genetics & development 9.6 (1999): 709-714. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/blob/master/papers/the-minimal-genome-concept-1999.pdf) :star::star::star::star::star:

**[5.2]** Hutchison, Clyde A., et al. "**Design and synthesis of a minimal bacterial genome.**" Science 351.6280 (2016): aad6253. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/design-and-synthesis-of-a-minimal-bacterial-genome-2016.pdf) :star::star::star::star::star:

> This is not a review.

**[5.3]** Haimovich, Adrian D., Paul Muir, and Farren J. Isaacs. "**Genomes by design.**" Nature Reviews Genetics 16.9 (2015): 501-516. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/genomes-by-design-2015.pdf) :star::star::star:

**[]** DNA architecture

---

## 6. Whole Cell Modeling

**[6.1]** Macklin, Derek N., Nicholas A. Ruggero, and Markus W. Covert. "**The future of whole-cell modeling.**" Current opinion in biotechnology 28 (2014): 111-115. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/the-future-of-whole-cell-modeling-2014.pdf) :star::star::star:

---

## 7. Intuition in Mathematical and Systems Biology

**[7.1]** Raue, Andreas, et al. "**Lessons learned from quantitative dynamical modeling in systems biology.**" PLoS One 8.9 (2013): e74335. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/lessons-learned-from-quantitative-dynamical-modeling-in-systems-biology-2013.pdf) :star::star::star::star::star:

**[7.2]** Gunawardena, Jeremy. "**Models in biology:‘accurate descriptions of our pathetic thinking’.**" BMC biology 12.1 (2014): 29. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/models-in-biology-accurate-descriptions-of-our-pathetic-thinking-2014.pdf) :star::star::star::star:

**[]** Del Vecchio

## 8. Environment and the Bioreactor

---

## 9. Ecosystems Engineering

**[9.1]** Mueller, U. G., and J. L. Sachs. "**Engineering microbiomes to improve plant and animal health.**" Trends in microbiology 23.10 (2015): 606-617. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/engineering-microbiomes-to-improve-plant-and-animal-health-2015.pdf) :star::star::star:

**[9.2]** Esvelt, Kevin M., et al. "**Concerning RNA-guided gene drives for the alteration of wild populations.**" Elife 3 (2014): e03401. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/emerging-technology-concerning-rna-guided-gene-drives-for-the-alteration-of-wild-populations-2014.pdf) :star::star::star:

**[9.3]** Brenner, Katie, Lingchong You, and Frances H. Arnold. "**Engineering microbial consortia: a new frontier in synthetic biology.**" Trends in biotechnology 26.9 (2008): 483-489. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/engineering-microbial-consortia-a-new-frontier-in-synthetic-biology-2008.pdf) :star::star::star::star::star:

---

## 10. Microbial Chemical Refineries

**[10.1]** Jullesson, David, et al. "**Impact of synthetic biology and metabolic engineering on industrial production of fine chemicals.**" Biotechnology advances 33.7 (2015): 1395-1402. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/blob/master/papers/impact-of-synthetic-biology-and-metabolic-engineering-on-industrial-production-of-fine-chemicals-2015.pdf) :star::star::star::star::star:

**[10.2]** Smanski, Michael J., et al. "**Synthetic biology to access and expand nature's chemical diversity.**" Nature Reviews Microbiology 14.3 (2016): 135. [[pdf]]()

---

## 11. Mammalian Synthetic Biology

**[11.1]** Lienert, Florian, et al. "**Synthetic biology in mammalian cells: next generation research tools and therapeutics.**" Nature Reviews Molecular Cell Biology 15.2 (2014): 95-107. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/synthetic-biology-in-mammalian-cells-next-generation-research-tools-and-therapeutics-2014.pdf) :star::star::star::star:

**[11.2]** Keung, Albert J., et al. "**Chromatin regulation at the frontier of synthetic biology.**" Nature Reviews Genetics 16.3 (2015): 159-171. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/chromatin-regulation-at-the-frontier-of-synthetic-biology-2015.pdf) :star::star::star::star:

**[11.3]** Ye, Haifeng, Dominique Aubel, and Martin Fussenegger. "**Synthetic mammalian gene circuits for biomedical applications.**" Current opinion in chemical biology 17.6 (2013): 910-917. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/blob/master/papers/synthetic-mammalian-gene-circuits-for-biomedical-applications-2013.pdf) :star::star::star:

**[11.4]** Markson, Joseph S., and Michael B. Elowitz. "**Synthetic biology of multicellular systems: new platforms and applications for animal cells and organisms.**" ACS synthetic biology 3.12 (2014): 875. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/synthetic-biology-of-multicellular-systems-new-platforms-and-applications-for-animal-cells-and-organisms-2014.pdf) :star::star::star::star::

**[11.5]** Esvelt, Kevin M., and Harris H. Wang. "**Genome‐scale engineering for systems and synthetic biology.**" Molecular systems biology 9.1 (2013): 641. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/genome-scale-engineering-for-systems-and-synthetic-biology-2013.pdf) :star::star::star::star::star::

**[11.6]** Esensten, Jonathan H., Jeffrey A. Bluestone, and Wendell A. Lim. "**Engineering therapeutic T cells: from synthetic biology to clinical trials.**" Annual Review of Pathology: Mechanisms of Disease 12 (2017): 305-330.

---

## 12. Plant Synthetic Biology and Photosynthesis

**[12.1]** Baltes, Nicholas J., and Daniel F. Voytas. "**Enabling plant synthetic biology through genome engineering.**" Trends in biotechnology 33.2 (2015): 120-131. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/enabling-plant-synthetic-biology-through-genome-engineering-2014.pdf) :star::star::star::star:

**[12.2]** Maurino, Veronica G., and Andreas PM Weber. "**Engineering photosynthesis in plants and synthetic microorganisms.**" Journal of experimental botany 64.3 (2013): 743-751. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/engineering-photosynthesis-in-plants-and-synthetic-microorganisms-2013.pdf) :star::star::star:

---

## 13. Biomaterials and Bioarchitecture

---

## 14. Cell-Free Systems

---

## 15. DNA Sequencing and Synthesis

**[15.1]** Mardis, Elaine R. "**DNA sequencing technologies: 2006-2016.**" Nature Protocols 12.2 (2017): 213-218. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/dna-sequencing-technologies-2006-2016-2017.pdf) :star::star::star:

**[15.2]** Kosuri, Sriram, and George M. Church. "**Large-scale de novo DNA synthesis: technologies and applications.**" Nature methods 11.5 (2014): 499-507. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/large-scale-de-novo-dna-synthesis-technologies-and-applications-2014.pdf) :star::star::star::star:

**[15.3]** Chao, Ran, Yongbo Yuan, and Huimin Zhao. "**Recent advances in DNA assembly technologies.**" FEMS yeast research 15.1 (2015): 1-9. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/recent-advances-in-dna-assembly-technologies-2015.pdf) :star::star::star:

**[15.4]** Kahl, Linda J., and Drew Endy. "**A survey of enabling technologies in synthetic biology.**" Journal of biological engineering 7.1 (2013): 13. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/survey-of-enabling-technologies-in-synthetic-biology-2013.pdf) :star::star::star::star:

---

## 16. Synthetic Biology and Evolution

**[16.1]** Packer, Michael S., and David R. Liu. "**Methods for the directed evolution of proteins.**" Nature Reviews Genetics 16.7 (2015): 379-394. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/methods-for-the-directed-evolution-of-proteins-2015.pdf) :star::star::star::star:

**[16.2]** Kacar, Betul, and Eric Gaucher. "**Towards the recapitulation of ancient history in the laboratory: combining synthetic biology with experimental evolution.**" arXiv preprint arXiv:1209.5032 (2012). [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/towards-the-recapitulation-of-ancient-history-in-the-laboratory-combining-synthetic-biology-with-experimental-evolution-2014.pdf) :star::star:

**[16.3]** Bayer, Travis S. "**Using synthetic biology to understand the evolution of gene expression.**" Current Biology 20.17 (2010): R772-R779. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/using-synthetic-biology-to-understand-the-evolution-of-gene-expression-2010.pdf) :star::star:

---

## 17. RNA Synthetic Biology

**[17.1]** Isaacs, Farren J., Daniel J. Dwyer, and James J. Collins. "**RNA synthetic biology.**" Nature biotechnology 24.5 (2006): 545-554. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/rna-synthetic-biology-2006.pdf) :star::star::star::star::star:

**[17.2]** McKeague, Maureen, Remus S. Wong, and Christina D. Smolke. "**Opportunities in the design and application of RNA for gene expression control.**" Nucleic acids research (2016): gkw151. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/opportunities-in-the-design-and-application-of-rna-for-gene-control-expression-2016.pdf) :star::star::star:

---

## 18. DNA Editing

**[18.1]** Makarova, Kira S., et al. "**Evolution and classification of the CRISPR–Cas systems.**" Nature Reviews Microbiology 9.6 (2011): 467-477. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/evolution-and-classification-of-the-crispr-cas-system-2011.pdf) :star::star::star::star::star:

**[18.2]** Hsu, Patrick D., Eric S. Lander, and Feng Zhang. "**Development and applications of CRISPR-Cas9 for genome engineering.**" Cell 157.6 (2014): 1262-1278. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/development-and-applications-of-crispr-cas9-for-genome-engineering-2014.pdf) :star::star::star::star::star:

---

## 19. OMICs Era of Biology

---

## 20. Biological inference and Reverse Engineering Biology

---

## 21. Computational Design of Biological Systems

---

## 22. iGEM and DIYBio

**[22.1]** Matheson, Susan. "**Engineering a Biological Revolution.**" Cell 168.3 (2017): 329-332. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/engineering-a-biological-revolution-2017.pdf) :star::star::star:

**[22.2]** Brown, James. "**The iGEM competition: building with biology.**" IET Synthetic Biology 1.1 (2007): 3-6. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/the-igem-competition-building-with-biology-2007.pdf) :star::star::star::star:

---

## 23. Synthetic Biology in Industry

**[23.1]** SynBioBeta [[link]](http://synbiobeta.com/)

**[23.2]** IndieBio [[link]](http://indiebio.co/)

**[23.3]** Bergin J. "**Synthetic Biology: Global Markets**” BBC Research. 2017. Web. 3 Mar. 2014. [[pdf]](https://github.com/crimsonigem/synthetic-biology-reading-roadmap/raw/master/papers/synthetic-biology-global-markets-2017.pdf) :star::star::star:

---

## 24 Art, Design, and Fashion

**[24.1]** Agapakis, Christina M. "**Designing synthetic biology.**" ACS synthetic biology 3.3 (2013): 121-128. [[pdf]](https://github.com/crimsonigem/synthetic-biology-reading-roadmap/raw/master/papers/designing-synthetic-biology-2013.pdf) :star::star:

**[24.2]** Oxman, Neri. "**Templating Design for Biology and Biology for Design.\***" Architectural Design 85.5 (2015): 100-107. [[pdf]](https://github.com/crimsonigem/synthetic-biology-reading-roadmap/raw/master/papers/templating-design-for-biology-and-biology-for-design-2015.pdf) :star::star::star:

**[24.3]** Dance, Amber. "**Science and Culture: The art of designing life.**" Proceedings of the National Academy of Sciences 112.49 (2015): 14999-15001. [[pdf]](https://github.com/crimsonigem/synthetic-biology-reading-roadmap/raw/master/papers/science-and-culture-the-art-of-designing-life-2015.pdf) :star::star::star:

**[24.4]** Descience [[link]](http://www.fashiondescience.com/)

**[24.5]** BioFabricate [[link]](http://www.biofabricate.co/)

---

## 25 Ethics and Biosafety

**[25.1]** Barras, Vincent, and Gilbert Greub. "**History of biological warfare and bioterrorism.**" Clinical Microbiology and Infection 20.6 (2014): 497-502. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/history-of-biological-warfare-and-bioterrorism-2014.pdf) :star::star::star:

**[25.2]** Douglas, Thomas, and Julian Savulescu. "**Synthetic biology and the ethics of knowledge.**" Journal of medical ethics 36.11 (2010): 687-693. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/synthetic-biology-and-the-ethics-of-knowledge-2010.pdf) :star::star::star:

**[25.3]** Gutmann, Amy. "**The ethics of synthetic biology: guiding principles for emerging technologies.**" Hastings Center Report 41.4 (2011): 17-22. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/the-ethics-of-synthetic-biology-guiding-principles-for-emerging-technologies-2011.pdf) :star::star::star:

**[25.4]** Redford, Kent H., William Adams, and Georgina M. Mace. "**Synthetic biology and conservation of nature: wicked problems and wicked solutions.**" PLoS Biol 11.4 (2013): e1001530. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/synthetic-biology-and-conservation-of-nature-wicked-problems-and-wicked-solutions-2013.pdf) :star::star::star:

**[25.5]** Oye, Kenneth A., et al. "**Regulating gene drives.**" Science 345.6197 (2014): 626-628. [[pdf]](https://github.com/crimsonigem/synthetic-biology-roadmap/raw/master/papers/regulating-gene-drives-2014.pdf) :star::star::star::star:

https://plato.stanford.edu/entries/systems-synthetic-biology/
