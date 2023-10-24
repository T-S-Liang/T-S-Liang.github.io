---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<table style="width:100%;border:None;border-spacing:0px;border-collapse:separate;margin-right:0;margin-left:0;font-size:0.95em;">
  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>2. "Self-paced Ensemble for Highly Imbalanced Massive Data Classification"</b>, 
      <br>
      <u>Zhining Liu</u>, 
      <a href="https://weicao1990.github.io/"> Wei Cao</a>, 
      <a href="https://scholar.google.com/citations?user=uBo3SJcAAAAJ&hl=en"> Zhifeng Gao</a>, 
      <a href="https://scholar.google.com/citations?user=pZBEnY8AAAAJ&hl=zh-CN"> Jiang Bian</a>, 
      <a href="https://scholar.google.com/citations?user=EezEcbgAAAAJ&hl=en"> Hechang Chen</a>, 
      <a href="http://yichang-cs.com/"> Yi Chang</a>, 
      <a href="https://www.microsoft.com/en-us/research/people/tyliu/"> Tie-Yan Liu</a>, 
      <br>
      <i>in 36th IEEE International Conference on Data Engineering (<b>ICDE 2020</b>).</i>
      <br>
      [<a href="https://arxiv.org/pdf/1909.03500v3.pdf">PDF</a>]
      [<a href="https://arxiv.org/abs/1909.03500v3">arXiv</a>] 
      [<a href="https://www.bilibili.com/video/BV1Fg411L7gk">Video(bilibili)</a>]
      [<a href="{{ site.baseurl }}files/ICDE_2020_SPE_slides.pdf">Slides</a>] 
      [<a href="https://zhuanlan.zhihu.com/p/86891438">Zhihu/知乎</a>] 
      [<a href="https://github.com/ZhiningLiu1998/self-paced-ensemble">Github</a>]
      [<a href="https://pypi.org/project/self-paced-ensemble">PyPI</a>]
    </td>
    <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/spe.png">
      <img src='/images/spe.png' width="300">
      </a>
    </td>
  </tr>
</table>

  ```bib
  @inproceedings{liu2020self,
    title={Self-paced Ensemble for Highly Imbalanced Massive Data Classification},
    author={Liu, Zhining and Cao, Wei and Gao, Zhifeng and Bian, Jiang and Chen, Hechang and Chang, Yi and Liu, Tie-Yan},
    booktitle={2020 IEEE 36th International Conference on Data Engineering (ICDE)},
    pages={841--852},
    year={2020},
    organization={IEEE}
  }
  ```
