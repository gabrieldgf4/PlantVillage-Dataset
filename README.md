# PlantVillage-Dataset

The PlantVillage dataset contains 54,304 images. The images span 14 crop species: Apple, Blueberry, Cherry, Corn, Grape, Orange, Peach, Bell Pepper, Potato, Raspberry, Soybean, Squash, Strawberry, Tomato. In containes images of 17 fungal diseases, 4 bacterial diseases, 2 mold (oomycete) diseases, 2 viral disease, and 1 disease caused by a mite. 12 crop species also have
images of healthy leaves that are not visibly affected by a disease. 

NOTE: The original image database is no longer available in the PlantVillage repository [www.plantvillage.org](www.plantvillage.org), therefore we got a copy of this database from another github account [https://github.com/spMohanty/PlantVillage-Dataset](https://github.com/spMohanty/PlantVillage-Dataset) and here we republished it. Besides, from the healthy leaf directories, we removed five figures that did not represent the characteristics that they should have. So we put them in a separate directory, named as "x_Removed_from_Healthy_leaves".

Original paper URL: [https://arxiv.org/abs/1511.08060](https://arxiv.org/abs/1511.08060)

    @article{DBLP:journals/corr/HughesS15,
	Author = {David P. Hughes and
               Marcel Salath{'{e} } },
	Title = {An open access repository of images on plant health to enable the
               development of mobile disease diagnostics through machine
               learning and crowdsourcing},
	journal   = {CoRR},
	volume    = {abs/1511.08060},
	year      = {2015},   
	url       = {http://arxiv.org/abs/1511.08060},
	archivePrefix = {arXiv},
	eprint    = {1511.08060},
	timestamp = {Mon, 13 Aug 2018 16:48:21 +0200},
	biburl    = {https://dblp.org/rec/bib/journals/corr/HughesS15},
	bibsource = {dblp computer science bibliography, https://dblp.org}
    }

You can download the dataset by:

    git clone https://github.com/gabrieldgf4/PlantVillage-Dataset.git
    cd PlantVillage-Dataset
