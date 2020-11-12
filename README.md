# Access to the data used for CONSULT benchmarking

This repository contains raw data and output reports we used for the study.

* Query summary reports used for sensitivity analysis of different tools:
    - [tools comparison](https://github.com/noraracht/lsh_raw_data/tree/main/tools_comparison)

* Runtime comparison of different tools:
    - [Drosophila queries](https://github.com/noraracht/lsh_raw_data/tree/main/runtime/dros_queries)
    - [TOL queries](https://github.com/noraracht/lsh_raw_data/tree/main/runtime/tol_queries)

* Query summary reports for GORG samples searched against TOL, GTDB and Bact/Arch Kraken using CONSULT:
    - [*m* = 3, *c* = 1](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_p3c1_consult)
    - [*m* = 3, *c* = 2](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_p3c2_consult)
    - [*m* = 4, *c* = 2](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_p4c2_consult)

* Query summary reports for GORG samples searched against TOL, GTDB and Bact/Arch Kraken using Kraken:
    - [conf = 0.00](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_conf0.00_kraken)
    - [conf = 0.02](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_conf0.02_kraken)
    - [conf = 0.05](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_conf0.05_kraken)
    
* False positives results evaluated with plant queries searched against TOL, GTDB and Bact/Arch Kraken with different settings:
    - [kraken](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_FP_kraken)
    - [consult](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_FP_consult)
    
* Extended parameter titration performed with GORG samples queried using GTDB database with variable *m* and *c* combinations:
    - [recall](https://github.com/noraracht/lsh_raw_data/tree/main/ext_par_titr_recall)
    - [false positives](https://github.com/noraracht/lsh_raw_data/tree/main/ext_par_titr_fp)
    
* Query summary reports and distance matrices for real Drosophila skims analysis:
    - [dros_real_skim_filt](https://github.com/noraracht/lsh_raw_data/tree/main/dros_real_skim_filt)
    
* Genome skims used for real Drosophila data analysis:
    - before clean up [deduplicated](https://drive.google.com/file/d/1m6-OCLy3_tML2LsnCG50MtOZI2cfOc4-/view?usp=sharing) and [with removed human reads](https://drive.google.com/file/d/1emUYbI2xn8Uxc9SdE_LbJawD7vXUzfxF/view?usp=sharing)
    - after clean up using [consult](https://drive.google.com/file/d/1zZCA3-Kmf0X2iR-zA3uIHKimjRohPwd2/view?usp=sharing) or [kraken](https://drive.google.com/file/d/1wJmA9WzZ9zuHAysZeVQLFIzX2r-V7JPf/view?usp=sharing)

* Custom Kraken libraries constructed using different genomic reference sets (upload in progress):
    - GTDB
    - TOL
    - [Bacterial/Archaeal Kraken](https://drive.google.com/file/d/1TEadVT1KPle_ljNKvd9nV7IY6VNfjOyT/view?usp=sharing)
    - [Human](https://drive.google.com/file/d/1lnMR2sf82_7Mloj1gKac-Fxt1_0vU9Ne/view?usp=sharing)

* Custom CONSULT libraries constructed using different genomic reference sets (upload in progress):
    - GTDB
    - TOL
    - [Bacterial/Archaeal Kraken](https://drive.google.com/file/d/1jeZB6b6aXl06BpPPsjM8oQA4xingJ1Dq/view?usp=sharing)
    
* Query sets used during testing:
    - [TOL query set](https://drive.google.com/file/d/1bBqU6uL1tNRmecHI052g0q7drrwybONm/view?usp=sharing)
    - [GORG query set](https://drive.google.com/file/d/1-C_ZCl2wbQk-QnGtk2z6yfLErNd_V87L/view?usp=sharing)
    

   
    
   
<!--* Query summary reports and distance matrices used for simulation experiment with overlapping contaminants:
    - [Dros_contam_overlap_k35_conf0.0.zip](https://github.com/noraracht/kraken_raw_data/blob/master/Dros_contam_overlap_k35_conf0.0.zip)-->


<!--* Query summary reports and distance matrices used for simulation experiment with overlapping contaminants:
    - [Dros_contam_overlap_k35_conf0.0.zip](https://github.com/noraracht/kraken_raw_data/blob/master/Dros_contam_overlap_k35_conf0.0.zip)-->
    
<!--* archive:   tar -zcvf BacArcKraken_FPplants_kraken_conf0.00.tar.gz BacArcKraken_FPplants_kraken_conf0.00
      unarchive: tar -xvzf BacArcKraken_FPplants_kraken_conf0.00.tar.gz-->
