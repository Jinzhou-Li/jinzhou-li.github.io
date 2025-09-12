---
layout: home
profile_picture:
  src: /assets/img/Zermatt2020.png
  alt: pic
---

Hi, I am an assistant professor in the [Department of Statistics and Data Science](https://www.stat.nus.edu.sg/) at the National University of Singapore (NUS). Previously, I was a postdoctoral fellow in the [Statistics Department](https://statistics.stanford.edu/) at Stanford University, advised by [Emmanuel Candès](https://candes.su.domains/). I obtained my PhD in the [Seminar for Statistics](https://math.ethz.ch/sfs), Department of Mathematics, from ETH Zürich, 
where I was supervised by [Marloes Maathuis](https://sites.google.com/view/marloes-maathuis) and [Nicolai Meinshausen](https://stat.ethz.ch/~nicolai/).

<br />
Email: jinzhouli@nus.edu.sg

<!---
Here are my [CV](/assets/file/CV_JinzhouLi.pdf), [Github](https://github.com/Jinzhou-Li) and [Google Scholar](https://scholar.google.com/citations?user=xtPvl4UAAAAJ&hl=en&oi=ao).
 --->

<!---
## Research interests
My research focuses on developing reliable methodologies to uncover scientific insights from data. 
In my current work, these insights take the form of conditional independence relations and causal mechanisms. 
Examples include identifying genotypes that are conditionally dependent on a trait given the other genotypes [(here)](https://academic.oup.com/jrsssb/article-abstract/86/4/966/7618756?redirectedFrom=fulltext),
modeling gene network [(here)](https://rss.onlinelibrary.wiley.com/doi/10.1111/rssb.12430),
estimating the causal effect of college education on extremely high wages [(here)](https://www.tandfonline.com/doi/full/10.1080/01621459.2023.2252141), and discovering disease-causing genes in patients 
with rare diseases (i.e., finding the ultimate cause of an observed effect, see [here](https://arxiv.org/abs/2410.12151)).
“Reliable” is achieved by incorporating error rate control into the developed methods, ensuring that the discoveries are largely correct. 
This includes controlling the widely used false discovery rate [(here)](https://rss.onlinelibrary.wiley.com/doi/10.1111/rssb.12430) 
or using simultaneous error bounds to check many sets if the task is more of an exploratory nature ([here](https://academic.oup.com/jrsssb/article-abstract/86/4/966/7618756?redirectedFrom=fulltext), [here](https://arxiv.org/abs/2401.03834)).
 --->


<br />

<br />

## Publications and preprints

### Statistical methodology
<!---
- **Which FDR control procedure should we choose?**
  <br>**Jinzhou Li<sup>\*</sup>**, Yuansi Chen<sup>\*</sup>, Emmanuel Candès (2024+).
  Working paper.
 --->

- **Root cause discovery via permutations and Cholesky decomposition.**
  <br>**Jinzhou Li**, Benjamin B. Chu, Ines F. Scheller, Julien Gagneur, Marloes H. Maathuis (2025).
  *Journal of the Royal Statistical Society, Series B, accepted.*
  <br>[\[arXiv\]](https://arxiv.org/abs/2410.12151)
  [\[codes\]](https://github.com/Jinzhou-Li/RootCauseDiscovery)

- **On the error control of invariant causal prediction.**
  <br>**Jinzhou Li** and Jelle J. Goeman (2024).
  Preprint.
  <br>[\[arXiv\]](https://arxiv.org/abs/2401.03834)
  [\[codes\]](https://github.com/Jinzhou-Li/ICPsimultaneousBounds)

- **Simultaneous false discovery proportion bounds via knockoffs and closed testing.**
  <br>**Jinzhou Li**, Marloes H. Maathuis and Jelle J. Goeman (2024).
  *Journal of the Royal Statistical Society, Series B, 86(4): 966-986.*
  <br>[\[published version\]](https://academic.oup.com/jrsssb/article-abstract/86/4/966/7618756?redirectedFrom=fulltext)
  [\[arXiv\]](https://arxiv.org/abs/2212.12822)
  [\[codes\]](https://github.com/Jinzhou-Li/KnockoffSimulFDP)

- **Estimation and Inference of Extremal Quantile Treatment Effects for Heavy-Tailed Distributions.**
  <br>David Deuber<sup>\*</sup>, **Jinzhou Li<sup>\*</sup>**, Sebastian Engelke and Marloes H. Maathuis (2023).
  *Journal of the American Statistical Association, 119(547): 2206-2216.*
  <br>[\[published version\]](https://www.tandfonline.com/doi/full/10.1080/01621459.2023.2252141)
  [\[arXiv\]](https://arxiv.org/abs/2110.06627)
  [\[codes\]](https://github.com/ddeuber/extremal-qte-heavy-tailed)

- **GGM knockoff filter: False discovery rate control for Gaussian graphical models.**
  <br>**Jinzhou Li** and Marloes H. Maathuis (2021).
  *Journal of the Royal Statistical Society, Series B, 83, 534-558.*
  <br>[\[published version\]](https://rss.onlinelibrary.wiley.com/doi/10.1111/rssb.12430)
  [\[arXiv\]](https://arxiv.org/abs/1908.11611)
  [\[codes\]](https://github.com/Jinzhou-Li/GGMKnockoffFilter-R)

### Applied Collaborations

- **Uncovering Heterogeneous Effects via Localized Feature Selection.**
  <br>Xiaoxia Liu, Jiaqi Gu, Zhaomeng Chen, Benjamin Chu, Linxi Liu, Tim Morrison, Robert R. Butler III, Jacob Edelson, **Jinzhou Li**, Frank M. Longo, Hua Tang, Iuliana Ionita-laza, Chiara Sabatti, Emmanuel Candès, Zihuai He (2025).
   <br>[\[bioRxiv\]](https://www.biorxiv.org/content/10.1101/2025.06.03.657761v1)

- **estimateR: An R package to estimate and monitor the effective reproductive number.**
  <br>Jérémie Scire, Jana S. Huisman, Ana Grosu, Daniel C. Angst, Adrian Lison, **Jinzhou Li**, Marloes H. Maathuis, Sebastian Bonhoeffer and Tanja Stadler (2023).
  *BMC Bioinformatics 24, 310.*
  <br>[\[published version\]](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05428-4)
  [\[medRxiv\]](https://www.medrxiv.org/content/10.1101/2022.06.30.22277095v1)
  [\[codes\]](https://github.com/covid-19-Re/estimateR)

- **Estimation and worldwide monitoring of the effective reproductive number of SARS-CoV-2.**
  <br>Jana S. Huisman, Jérémie Scire, Daniel C. Angst, **Jinzhou Li**, Richard A. Neher, Marloes H. Maathuis, Sebastian Bonhoeffer and Tanja Stadler (2022).
  *eLife 11, e71345.*
  <br>[\[published version\]](https://elifesciences.org/articles/71345)
  [\[medRxiv\]](https://www.medrxiv.org/content/10.1101/2020.11.26.20239368v4)
  [\[codes\]](https://github.com/covid-19-Re/paper-code)
  [\[website\]](https://ibz-shiny.ethz.ch/covid-19-re-international/)


