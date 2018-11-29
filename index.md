<!-- You can use the [editor on GitHub](https://github.com/maple-repair/expression-templates/edit/master/index.md) to maintain and preview the content for your website in Markdown files. -->

<!-- # Automated Program Repair using Formal Specifications. -->

## Abstract
  We present an automated approach to repair programs using formal
  verification and expression templates. In our approach, an input program
  is first verified against its formal specification to discover
  potentially buggy statements. For each of these statements, we identify
  the expression that needs to be repaired and set up a template patch
  which is a linear expression composed of the program's variables and
  unknown coefficients. Then, we analyze the template-patched program
  against its specification to collect a set of constraints of the template
  patch. This constraint set will be solved by a constraint solving
  technique using Farkas' lemma to identify the unknown coefficients,
  consequently discovering the patch. We implement our approach in a tool
  called {\maple} and evaluate it with various buggy programs from a widely
  used benchmark {\TCAS} as well as a synthetic, yet challenging benchmark
  containing recursive programs. Our tool outperforms state-of-the-art
  program repair tools in returning desired patches.

## Experiment data for Maple in the benchmark **Recursion**
In our paper's experiment section, we have 2 benchmarks, **TCAS** and a
newly-created **Recursion**. The details about the second benchmark is provided
in [Github](https://github.com/maple-repair/recursive-benchmark).


## People
- Dr. Wei-Ngan Chin (Associate Professor - National University of Singapore)
- Dr. Quang-Trung Ta (Research Fellow - National University of Singapore) 
- Thanh-Toan Nguyen (PhD Candidate - National University of Singapore)

<!-- ## Our VMCAI paper -->

<!-- ## Header 2 -->
<!-- ### Header 3 -->

<!-- - Bulleted -->
<!-- - List -->

<!-- 1. Numbered -->
<!-- 2. List -->

<!-- **Bold** and _Italic_ and `Code` text -->

<!-- [Link](url) and ![Image](src) -->
<!-- ``` -->

<!-- For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/). -->

<!-- ### Jekyll Themes -->

<!-- Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/maple-repair/expression-templates/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file. -->

<!-- ### Support or Contact -->

<!-- Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out. -->
