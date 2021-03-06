# bigNN: an open-source big data toolkit focused on biomedical sentence classification

<p align="justify">Every single day, a large amount of text data is generated by different medical data sources, such as scientific literature, medical web pages, health related social media posts, clinical notes, and drug reviews. Processing this data in an efficient manner is a really daunting task without the help of clever computational strategies, and it makes text classification as an imperative and a major operation to big data text analytics. In this contribution, we developed an open-source software for big data text classification called <strong>bigNN</strong>. It implements a word2vec neural network model over Apache Spark to aim at big data sentence classification in a timely fashion. The software offers a graphical user interface, and it facilitates reproducible research in sentence analysis by allowing users to configure different sets of Apache Spark and word2vec neural network parameters. Furthermore, we introduce application of <strong>bigNN</strong> in medical informatics domain. <strong> bigNN </strong> is fully documented and it is publicly and freely available at https://github.com/bircatmcri/bigNN.
</p>

<p align="justify">
The <strong>bigNN</strong> includes the following packages: 

| Package Name        | Description |
| ------------- |-------------|
| <strong>edu.mfldclin.mcrf.bignn.gui</strong>  | Implementation of the graphical user interface |
| <strong>edu.mfldclin.mcrf.bignn.setting</strong> | Implementation of pre-defined and user-defined settings required to the system|
| <strong>edu.mfldclin.mcrf.bignn.learning</strong> | Implementation of text pre-processing and neural network learning model|
| <strong>edu.mfldclin.mcrf.bignn.evaluation</strong> | It evaluates the neural network predictive model|
</p>

### Requirements:
+ Apache Spark 2.10
+ Java2SE 8


### bigNN software architectural model:
<p align="justify">
The <strong>bigNN</strong> software architectural model is shown in includes the following figure.  
</p>


![alt text](https://github.com/bircatmcri/bigNN/blob/master/bigNN%20architecture.png  "bigNN software architectural model")
</p>

---

### Collaborators:

1) Ahmad P. Tafti (Marshfield Clinic Research Institute)
2) Ehsun Behravesh (IEEE Member)
3) Mehdi Assefi (University of Georgia)
4) Eric LaRose (Marshfield Clinic Research Institute)
5) Jonathan Badger (Marshfield Clinic Research Institute)
6) John Mayer (Marshfield Clinic Research Institute)
7) AnHai Doan (University of Wisconsin-Madison)
8) David Page (University of Wisconsin-Madison)
9) Peggy Peissig (Marshfield Clinic Research Institute)




### Acknowledgment:

<p align="justify">
The project described was supported by the Clinical and Translational Science Award (CTSA) program, through the NIH National Center for Advancing Translational Sciences (NCATS), grant UL1TR000427. The content is solely the responsibility of the authors and does not necessarily represent the official views of the NIH.</p>



### Publications:

<p align="justify">
The workflow and architectural model of the <strong>bigNN</strong> is fully explained in <strong>[1]</strong>. Any publication using the <strong>bigNN</strong> would encourage to cite the two following papers. Thanks! 

<p align="justify">
<strong>[1]</strong> Tafti, A.P., Behravesh, E., Assefi, M., LaRose, E., Badger, J., Mayer, J., Doan, A., Page, D., Peissig, P. 2017. bigNN: an open-source big data toolkit focused on biomedical sentence classification. IEEE BIG DATA 2017. <a href="https://github.com/bircatmcri/bigNN/blob/master/bigNN.pdf" target="_blank">[<strong>Paper</strong>]</a>

<strong>[2]</strong> Tafti, A.P., Badger, J., LaRose, E., Shirzadi, E., Mahnke, A., Mayer, J., Ye, Z., Page, D. and Peissig, P., 2017. Adverse Drug Event Discovery Using Biomedical Literature: A Big Data Neural Network Adventure. JMIR medical informatics, 5(4), p.e51.</strong> <a href="https://github.com/bircatmcri/bigNN/blob/master/ADEs_JMIR.pdf" target="_blank">[<strong>Paper</strong>]</a>

</p>





