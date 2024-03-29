# TransposonUltimate

## TransposonUltimate: a holistic bundle of tools for transposon identification

---

This is the official GitHub page of TransposonUltimate. You will find four pages with powerful tools for transposon identification here:

* [Transposon Annotation Tools](https://github.com/DerKevinRiehl/transposon_annotation_tools)
This page contains conda packaged versions of different transposon annotation tools, including MUSTv2, HelitronScanner, SineFinder, MiteTracker, MiteFinderII, SineScan, TirVish, LtrHarvest, TransposonPSI, TransposonNCBICDD1000.

* [Transposon Classifier "RFSB"](https://github.com/DerKevinRiehl/transposon_classifier_rfsb)
This page contains the transposon classification module "RFSB" (Random Forest Selective Binary), that can classify any given DNA sequence into a hierarchical taxonomic scheme.
Also, you can use this software to train models for other databases on your own.

* [Transposon Annotator "reasonaTE"](https://github.com/DerKevinRiehl/transposon_annotation_reasonaTE)
This page contains the transposon annotation pipeline "reasonaTE", that is an ensemble of 13 annotation tools and combines the knowledge of different annotation approaches.

* [Transposition Event Detector "deTEct"](https://github.com/DerKevinRiehl/transposition_detector_deTEct)
This page contains the transposition event detection module "deTEct", that uses structural variants discovered by Sniffles and PBSV to match these against transposon annotations. As a result, it allows for the observation of potential transposition events.

---

![alt text](https://github.com/DerKevinRiehl/TransposonUltimate/blob/main/Pipelines.PNG)


---

## Materials
Please find all related materials here:
* https://cellgeni.cog.sanger.ac.uk/browser.html?shared=transposonultimate/ 

Please find the TransposonDB as fasta file here:
* https://doi.org/10.5281/zenodo.5484069

---

## Citations
Please cite our paper if you find TransposonUltimate useful:

Kevin Riehl, Cristian Riccio, Eric A Miska, Martin Hemberg, TransposonUltimate: software for transposon classification, annotation and detection, Nucleic Acids Research, 2022; gkac136, https://doi.org/10.1093/nar/gkac136

```
@article{riehl2022transposonultimate,
  title={TransposonUltimate: software for transposon classification, annotation and detection},
  author={Riehl, Kevin and Riccio, Cristian and Miska, Eric and Hemberg, Martin},
  journal={Nucleic Acids Research},
  year={2022}
}
```

## Acknowledgements
We would like to thank Sarah Buddle, Simone Procaccia, Fu Xiang Quah and Alexandra Dallaire for their assistance with testing and debugging the software.
