---
title: "Awards"
---

{% from "_macros.html" import paper, button, youtube %}

# Awards

At MIDL 2025, we were proud to recognize outstanding contributions through our Best Paper Awards. These awards highlight work that demonstrated not only high scientific quality but also clear and engaging presentation — whether delivered as an oral talk or a poster.

All full-length papers presented at the conference were eligible. An independent committee with no conflicts of interest carefully reviewed candidates, considering both the rigor and impact of the research and the effectiveness of its communication.

These awards celebrate the spirit of MIDL — where cutting-edge methods meet clarity, accessibility, and meaningful discussion.

## Best Poster Award

#### Winner
[% .papers %]
{{ paper('Self-Supervised Synthetic Cerebral Vessel Tree Generation using Semantic Signed Distance Fields',
        'Thijs P. Kuipers, Praneeta R. Konduri, Erik J Bekkers, Henk Marquering',
        openreview='https://openreview.net/forum?id=A6iHYOLrLd',
        abstract="Advances in in-silico clinical trails for the development of novel treatment and devices for acute ischemic stroke have driven the creation of synthetic virtual patient populations to address the lack of large real-world datasets. Recent work proposed a method for generating semantic vascular centerline tree of the major cerebral arteries using pointcloud diffusion. However, this approach relies on separate post-processing algorithms to reconstruct the vessel tree topology, which does not generalize well to more topologically complex trees. To overcome this limitation, we introduce semantic signed distance fields for modeling cerebral vessel trees in a fully self-supervised manner. Our approach bypasses the need for separate reconstruction of the tree topology, and can be trained directly on shape-surfaces. Our method combines a variational autoencoder for encoding shapes to robust latent shape representations with a latent-diffusion model for generating synthetic vessel trees.  By generating surface geometry directly, our approach eliminates the need for post-processing steps, enabling the generation of high-quality and topologically complex cerebral vessel trees.")
}}
[% / %]

#### Runner-up
[% .papers %]
{{ paper('HIEGNet: A Heterogenous Graph Neural Network Including the Immune Environment in Glomeruli Classification',
        'Niklas Kormann, Masoud Ramuz, Zeeshan Nisar, Nadine S. Schaadt, Hendrik Annuth, Benjamin Doerr, Friedrich Feuerhake, Thomas Lampert, Johannes F. Lutzeyer',
        openreview='https://openreview.net/forum?id=zt69HTmOjP',
        abstract="Graph Neural Networks (GNNs) have recently been found to excel in histopathology. However, an important histopathological task, where GNNs have not been extensively explored, is the classification of glomeruli health as an important indicator in nephropathology. This task presents unique difficulties, particularly for the graph construction, i.e., the identification of nodes, edges, and informative features. In this work, we propose a pipeline composed of different traditional and machine learning-based computer vision techniques to identify nodes, edges, and their corresponding features to form a heterogeneous graph. We then proceed to propose a novel heterogeneous GNN architecture for glomeruli classification, called HIEGNet, that integrates both glomeruli and their surrounding immune cells. Hence, HIEGNet is able to consider the immune environment of each glomerulus in its classification. Our HIEGNet was trained and tested on a dataset of Whole Slide Images from kidney transplant patients. Experimental results demonstrate that HIEGNet outperforms several baseline models and generalises best between patients among all baseline models. Our implementation is publicly available at https://github.com/nklsKrmnn/HIEGNet.git.")
}}
[% / %]


## Best Oral Award
#### Winner
[% .papers %]
{{ paper('MedVAE: Efficient Automated Interpretation of Medical Images with Large-Scale Generalizable Autoencoders',
        'Maya Varma, Ashwin Kumar, Rogier Van der Sluijs, Sophie Ostmeier, Louis Blankemeier, Pierre Joseph Marcel Chambon, Christian Bluethgen, Jip Prince, Curtis Langlotz, Akshay S Chaudhari',
        openreview='https://openreview.net/forum?id=jNmvKHniMe',
        abstract="Medical images are acquired at high resolutions with large fields of view in order to capture fine-grained features necessary for clinical decision-making. Consequently, training deep learning models on medical images can incur large computational costs. In this work, we address the challenge of downsizing medical images in order to improve downstream computational efficiency while preserving clinically-relevant features. We introduce MedVAE, a family of six large-scale 2D and 3D autoencoders capable of encoding medical images as downsized latent representations and decoding latent representations back to high-resolution images. We train MedVAE autoencoders using a novel two-stage training approach with 1,052,730 medical images. Across diverse tasks obtained from 20 medical image datasets, we demonstrate that (1) utilizing MedVAE latent representations in place of high-resolution images when training downstream models can lead to efficiency benefits (up to 70x improvement in throughput) while simultaneously preserving clinically-relevant features and (2) MedVAE can decode latent representations back to high-resolution images with high fidelity. Our work demonstrates that large-scale, generalizable autoencoders can help address critical efficiency challenges in the medical domain.\n\nCode: https://github.com/StanfordMIMI/MedVAE")
}}
[% / %]

#### Runner-up
[% .papers %]
{{ paper('PRISM: High-Resolution & Precise Counterfactual Medical Image Generation using Language-guided Stable Diffusion',
        'Amar Kumar, Anita Kriz, Mohammad Havaei, Tal Arbel',
        openreview='Amar Kumar, Anita Kriz, Mohammad Havaei, Tal Arbel',
        abstract="Developing reliable and generalizable deep learning systems for medical imaging faces significant obstacles due to spurious correlations, data imbalances, and limited text annotations in datasets. Addressing these challenges requires architectures robust to the unique complexities posed by medical imaging data. The rapid advancements in vision-language foundation models within the natural image domain prompt the question of how they can be adapted for medical imaging tasks. In this work, we present PRISM, a framework that leverages foundation models to generate high-resolution, language-guided medical image counterfactuals using Stable Diffusion. Our approach demonstrates unprecedented precision in selectively modifying spurious correlations (the medical devices) and disease features, enabling the removal and addition of specific attributes while preserving other image characteristics. Through extensive evaluation, we show how PRISM advances counterfactual generation and enables the development of more robust downstream classifiers for clinically deployable solutions. To facilitate broader adoption and research, we make our code publicly available at https://github.com/Amarkr1/PRISM.")
}}
[% / %]

## Outstanding reviewer awards

MIDL 2025 recognized a group of Outstanding Reviewers whose contributions go above and beyond in supporting the peer review process — a cornerstone of our conference. Reviewers were selected based on the quality of their reviews, including clarity, constructiveness, and depth of feedback, as well as their timeliness and responsiveness during the discussion phase. Nominations were made by the Area Chairs, who observed reviewer engagement and impact throughout the review cycle.

These reviewers played a vital role in shaping the scientific program, and we thank them for their exceptional service to the MIDL community.

* Alceu Bissoto ​
* Ananya Jana​
* Anne-Marie Rickmann ​
* Elias Eulig ​
* Erwan Kerrien ​
* Florentin Bieder ​
* Harini Veeraraghavan ​
* Hoel Kervadec ​​
* Marianne Rakic ​​
* Matthias P Heinrich ​​
* Mischa Dombrowski ​​
* Nick Konz ​​
* Nima Fathi ​​
* Olivier Salvado ​​
* Sania Eskandari ​​
* Walid Yassine ​
