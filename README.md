# :cityscape: TUM - FAÇADE :cityscape:
**Benchmark for semantic façade segmentation on MLS point clouds** 

![](https://github.com/OloOcki/tum-facade/blob/main/img/introGif.gif)

[<img src="https://github.com/OloOcki/tum-facade/blob/main/img/button1.png" width="150"/>](https://dataserv.ub.tum.de/index.php/s/m1636761.001)
[<img src="https://github.com/OloOcki/tum-facade/blob/main/img/button2.png" width="150"/>](https://mediatum.ub.tum.de/export/1636761/bibtex)
[<img src="https://github.com/OloOcki/tum-facade/blob/main/img/button3.png" width="150"/>](https://mediatum.ub.tum.de/1636761) 

## :star2: Highlights :star2:

- MLS point clouds with **facade-level labels** (i.e., windows, doors, balconies, moldings, etc.)
- **14 annotated facades** and 15 non-annotated for further benchmark extension or testing
- **~118 mln** annotated points
- in **local** and **global** (i.e., UTM) coordinate reference system
- settings file for **adding your own data**

## :mag_right: Annotated dataset

![](https://github.com/OloOcki/tum-facade/blob/main/img/arch2022gifDataset.gif)

<p float="center">
    <img src="https://github.com/OloOcki/tum-facade/blob/main/img/bldID60table.png" width="95%" title="Available classes table"/>
</p>


## :bar_chart: Statistics

<p float="center">
    <img src="https://github.com/OloOcki/tum-facade/blob/main/img/distributionChart.png" width="100%" title="Distribution of annotated points"/>
</p>


## :construction_worker: Build-upon the dataset

- Annotate the outstanding building point clouds in the dataset, contact us (e.g., olaf.wysocki@tum.de), and extend the repository of the open façades!
- **OR** use our open-source-based approach and create a new open point cloud dataset!

## :mortar_board: Publications

In the linked paper you will find the comprehensive description of this dataset, how we achieved it, and the landscape of the point cloud benchmark datasets.
If you use this dataset please cite either:

1. The paper

```plain
@article{wysockiTUMFACADE,
	author = {Wysocki, O. and Hoegner, L. and Stilla, U.},
	title = {TUM-FAÇADE: REVIEWING AND ENRICHING POINT CLOUD BENCHMARKS FOR FAÇADE SEGMENTATION},
	journal = {The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences},
	volume = {XLVI-2/W1-2022},
	year = {2022},
	pages = {529--536},
	url = {https://www.int-arch-photogramm-remote-sens-spatial-inf-sci.net/XLVI-2-W1-2022/529/2022/},
	doi = {10.5194/isprs-archives-XLVI-2-W1-2022-529-2022},
```
2. The dataset

```plain
@misc{mediatum1636761, 
	author = {Wysocki, Olaf  and Zhang, Jiarui  and Stilla, Uwe},
	title = {TUM-FAÇADE},
	publisher = {Technical University of Munich},
	url = {https://mediatum.ub.tum.de/1636761},
	type = {Dataset},
	year = {2021},
	doi = {10.14459/2021mp1636761.001},
	keywords = {MLS point clouds; semantic segmentation, 3D reconstruction, facade reconstruction},
	language = {en},
    
```


## :handshake: Acknowledgments 

This work wouldn't be possible without [Zhu et al.](https://doi.org/10.3390/rs12111875) and their excellent [TUM-MLS-2016 dataset](https://www.pf.bgu.tum.de/pub/testdaten.html). Thank you!    
We are indebted to [Jiarui Zhang](https://de.linkedin.com/in/jiarui-zhang-20bb3618b) for his diligent work in the annotation process. 
Thank you Hitachi group for releasing the [Semantic Segmentation Editor](https://github.com/Hitachi-Automotive-And-Industry-Lab/semantic-segmentation-editor) as a user-friendly open-source tool that we could easily adapt to our needs. 

Last but not least, thank you [Matrone et al.](https://doi.org/10.5194/isprs-archives-XLIII-B2-2020-1419-2020) for the inspiring [ArCH dataset](http://archdataset.polito.it/)! Go ahead, check it out, and test your algorithms there too!


