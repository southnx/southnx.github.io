

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**Nan Xi**, Jingjing Meng, Junsong Yuan, “Chain-of-Look Prompting for Verb-centric Surgical Triplet Recognition in Endoscopic Videos”, in Proc. ACM International Conf. on Multimedia (ACM MM), 2023

**Nan Xi**, Jingjing Meng, Junsong Yuan, “Open Set Video HOI detection from Action- centric Chain-of-Look Prompting”. in Proceedings of the IEEE International Confer- ence on Computer Vision (ICCV), 2023

Qinji Yu, **Nan Xi**, Junsong Yuan, Zhouzi Yu, Kang Dang, Xiaowei Ding, “Source-Free Domain Adaptation for Medical Image Segmentation via Prototype-Anchored Feature Alignment and Contrastive Learning”, in International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI), 2023

**Nan Xi**, Jingjing Meng, Junsong Yuan, “Forest Graph Convolution Network for Sur- gical Action Triplets Recognition in Endoscopic Videos”, in IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), 2022

Hanyu Li*, Sabrina Racine-Brzostek*, **Nan Xi***, Jiwen Luo, Zhen Zhao, Junsong Yuan (* equal contribution) “Learning to Detect Monoclonal Protein in Electrophore- sis Images”, in IEEE International Conference on Visual Communications and Image Processing (VCIP), 2021

**Nan Xi**. “Semi-supervised Attentive Mutual-info Generative Adversarial Network for Brain Tumor Segmentation”, in Proceedings of the 34th International Conference on Image and Vision Computing New Zealand (IVCNZ), 2019
