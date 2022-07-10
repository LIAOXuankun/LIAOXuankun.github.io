## Biography

I'm currently a year 2 Phd student in the [Database Group](https://www.comp.hkbu.edu.hk/~db/index.html) of the [Department of Computer Science](https://www.comp.hkbu.edu.hk/v1/), Hong Kong Baptist University (HKBU) supervised by [Prof. Jianliang Xu](https://www.comp.hkbu.edu.hk/~xujl/). I obtained my Bachelor's degree from the School of Electronic Information and Communications [(EIC)](http://ei.hust.edu.cn/English/Home.htm), Huazhong University of Science and Technology [(HUST)](https://www.hust.edu.cn/) in 2020.

## Research Interests

I am interested in graph data management, especially distributed and parallel graph computation. I also have interest in developing efficient algorithms for streaming graph computation.  

## Contact

Email: xkliao@comp.hkbu.edu.hk

##Publications [[DBLP]](https://dblp.org/pid/313/9191.html) [[Google Scholar]](https://scholar.google.com/citations?hl=zh-CN&user=s9Kv6Q4AAAAJ)

1. @article{10.14778/3529337.3529340,
author = {Liao, Xuankun and Liu, Qing and Jiang, Jiaxin and Huang, Xin and Xu, Jianliang and Choi, Byron},
title = {Distributed D-Core Decomposition over Large Directed Graphs},
year = {2022},
issue_date = {April 2022},
publisher = {VLDB Endowment},
volume = {15},
number = {8},
issn = {2150-8097},
url = {https://doi.org/10.14778/3529337.3529340},
doi = {10.14778/3529337.3529340},
abstract = {Given a directed graph G and integers k and l, a D-core is the maximal subgraph H ⊆ G such that for every vertex of H, its in-degree and out-degree are no smaller than k and l, respectively. For a directed graph G, the problem of D-core decomposition aims to compute the non-empty D-cores for all possible values of k and l. In the literature, several peeling-based algorithms have been proposed to handle D-core decomposition. However, the peeling-based algorithms that work in a sequential fashion and require global graph information during processing are mainly designed for centralized settings, which cannot handle large-scale graphs efficiently in distributed settings. Motivated by this, we study the distributed D-core decomposition problem in this paper. We start by defining a concept called anchored coreness, based on which we propose a new H-index-based algorithm for distributed D-core decomposition. Furthermore, we devise a novel concept, namely skyline coreness, and show that the D-core decomposition problem is equivalent to the computation of skyline corenesses for all vertices. We design an efficient D-index to compute the skyline corenesses distributedly. We implement the proposed algorithms under both vertex-centric and block-centric distributed graph processing frameworks. Moreover, we theoretically analyze the algorithm and message complexities. Extensive experiments on large real-world graphs with billions of edges demonstrate the efficiency of the proposed algorithms in terms of both the running time and communication overhead.},
journal = {Proc. VLDB Endow.},
month = {apr},
pages = {1546–1558},
numpages = {13}
}

## Honors & Awards
1. Outstanding Graduate, HUST, 2020 


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/LIAOXuankun/LIAOXuankun.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
