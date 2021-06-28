# Access to the data used for CONSULT benchmarking

This repository contains raw data and output reports we used for the study.

* Query summary reports used for sensitivity analysis of different tools:
    - [tools comparison](https://github.com/noraracht/lsh_raw_data/tree/main/tools_comparison)

* Runtime comparison of different tools:
    - [Drosophila queries](https://github.com/noraracht/lsh_raw_data/tree/main/runtime/dros_queries)
    - [TOL queries](https://github.com/noraracht/lsh_raw_data/tree/main/runtime/tol_queries)

* Query summary reports for GORG samples searched against TOL, GTDB and Bact/Arch Kraken using CONSULT:
    - [*p* = 3, *c* = 1](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_p3c1_consult)
    - [*p* = 3, *c* = 2](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_p3c2_consult)
    - [*p* = 4, *c* = 2](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_p4c2_consult)

* Query summary reports for GORG samples searched against TOL, GTDB and Bact/Arch Kraken using Kraken:
    - [conf = 0.00](https://drive.google.com/file/d/1Qq3QWThO6Vpc2fSUhjZS6-vGzHtNyn2-/view?usp=sharing)
    - [conf = 0.02](https://drive.google.com/file/d/184A5bLZi3lcyxc66j0KWTb4RwY8eWRjt/view?usp=sharing)
    - [conf = 0.04](https://drive.google.com/file/d/1iyxIhcGKaK2-WiGW3ekEWbNvZoKdfsnD/view?usp=sharing)
    - [conf = 0.05](https://drive.google.com/file/d/1ouJCVwg2tokg36irvZn0B-QefHZU7bbO/view?usp=sharing)
   
    
* False positives results evaluated with plant queries searched against TOL, GTDB and Bact/Arch Kraken with different settings:
    - [kraken](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_FP_kraken)
    - [consult](https://github.com/noraracht/lsh_raw_data/tree/main/gorg_FP_consult)
    
* Extended parameter titration performed with GORG samples queried using GTDB database with variable *p* and *c* combinations:
    - [recall](https://github.com/noraracht/lsh_raw_data/tree/main/ext_par_titr_recall)
    - [false positives](https://github.com/noraracht/lsh_raw_data/tree/main/ext_par_titr_fp)
    
* Query summary reports and distance matrices for real Drosophila skims analysis:
    - [dros_real_skim_filt](https://github.com/noraracht/lsh_raw_data/tree/main/dros_real_skim_filt)
    
* Genome skims used for real Drosophila data analysis:
    - before clean up [deduplicated](https://drive.google.com/file/d/1m6-OCLy3_tML2LsnCG50MtOZI2cfOc4-/view?usp=sharing) and [with removed human reads](https://drive.google.com/file/d/1emUYbI2xn8Uxc9SdE_LbJawD7vXUzfxF/view?usp=sharing)
    - after clean up using [consult](https://drive.google.com/file/d/1fCwz07JCRFb2fWLJXc1ELMeBHvm118ph/view?usp=sharing) or [kraken](https://drive.google.com/file/d/102oKp3CmutgHxmAWeVZELwgR5wRj-ODV/view?usp=sharing)

* Custom Kraken libraries constructed using different genomic reference sets:
    - [GTDB](https://drive.google.com/file/d/1PEIq70XKL8BSVc3WasL1mxCRmnHzUXPP/view?usp=sharing)
    - [TOL](https://drive.google.com/file/d/1kX7uvoK0UaBxx63c4o_biWUTPX-3gRGf/view?usp=sharing)
    - [GTDB orig taxonomy](https://drive.google.com/file/d/1hX9TykpwDsH26MRct63rzoET5aeHPolh/view?usp=sharing)
    - [TOL orig taxonomy](https://drive.google.com/file/d/1jEOSKxjl9phZ85t23XwG57XET_7RmsiX/view?usp=sharing)
    - [Bacterial/Archaeal Kraken](https://drive.google.com/file/d/1TEadVT1KPle_ljNKvd9nV7IY6VNfjOyT/view?usp=sharing)
    - [Human](https://drive.google.com/file/d/1lnMR2sf82_7Mloj1gKac-Fxt1_0vU9Ne/view?usp=sharing)
    
* Custom CONSULT libraries constructed using different genomic reference sets:
    - [GTDB](https://tera-trees.com/data/consult/v1.0.0/all_nbrhood_kmers_k32_p3l2clmn7_K15-map2-171_gtdb.tar.gz)
    - [TOL](https://tera-trees.com/data/consult/v1.0.0/all_nbrhood_kmers_k32_p3l2clmn7_K15-map2-171_ToL.tar.gz)
    - [Bacterial/Archaeal Kraken](https://tera-trees.com/data/consult/v1.0.0/all_nbrhood_kmers_k32_p3l2clmn7_K15-map2-171_kraken.tar.gz)
  
* Query sets used during testing:
    - [TOL query set](https://drive.google.com/file/d/1bBqU6uL1tNRmecHI052g0q7drrwybONm/view?usp=sharing)
    - [GORG query set](https://drive.google.com/file/d/1-C_ZCl2wbQk-QnGtk2z6yfLErNd_V87L/view?usp=sharing)

* Mitochondrial assembly:
    * Original sequencing data:
        - [Filtered reads](https://drive.google.com/file/d/1I1lFSuS0ltdk4tuOnLM-G3lUYvJ4HvWv/view?usp=sharing)
        - [Unfiltered reads](https://drive.google.com/file/d/1oywrGq6pQq9wjP-SFmt8qaOxdQ13eOrH/view?usp=sharing)

    * Read filtering:
        - [Mitochondrial CONSULT database](https://tera-trees.com/data/consult/v1.0.0/consult_mito_k32_p3l2clmn7_K15_tag2_v171.tar.gz)
        
    * Assemblies:
        - [From filtered reads](https://github.com/noraracht/lsh_raw_data/tree/main/filt_stdspades_cseq_n1_scaffolds)
        - [From unfiltered reads](https://github.com/noraracht/lsh_raw_data/tree/main/notfilt_final_mito_n1_scaffolds)
       
    * Annotation reports:
        - [Original assemblies](https://github.com/noraracht/lsh_raw_data/tree/main/mitos_annot_original)
        - [Filtered reads](https://github.com/noraracht/lsh_raw_data/tree/main/mitos_annot_filt)
        - [Unfiltered reads](https://github.com/noraracht/lsh_raw_data/tree/main/mitos_annot_unfilt)
        
    * Summary tables:
        - [Filtered vs unfiltered](https://github.com/noraracht/lsh_scripts/blob/main/combined_horizontal_mitoS_filt_unfilt_full.csv)
        - [All conditions](https://github.com/noraracht/lsh_scripts/blob/main/combined_mitoS_filt_unfilt_originalDanish_full.csv)

* Chloroplast assembly:
    * Original sequencing data:
        - [Filtered reads-upload in progress]()
        - [Unfiltered reads-upload in progress]()
        
   * Assemblies:
        - [From filtered reads](https://drive.google.com/file/d/1UcI9xt_sxUjZ-vb0Pp-BdkBDkJBgQxYz/view?usp=sharing)
        - [From unfiltered reads]()
       
    * Annotations:
        - [Outputs](https://drive.google.com/file/d/1gyLmDUmMlMrWpsDvf8VpgUspL3ktA1wc/view?usp=sharing)
        
 * Copy of CONSULT libraries are also available from goggle drive:
    - [GTDB](https://drive.google.com/file/d/1MQJAXmZiTurumlZpvNoMLB0tKWGM_VE4/view?usp=sharing)
    - [TOL](https://drive.google.com/file/d/1sA9HFjWoU2jZ2vjd98pHVDEFRzOKMImk/view?usp=sharing)
    - [Bacterial/Archaeal Kraken](https://drive.google.com/file/d/1jeZB6b6aXl06BpPPsjM8oQA4xingJ1Dq/view?usp=sharing)
    - [Mitochondrial CONSULT database](https://drive.google.com/file/d/1mFD3dYFrJKqUkWlkRHbrQt-6eG-_K5vI/view?usp=sharing)
    - [Plastid CONSULT database](https://drive.google.com/file/d/1ifymaBvHK6LmAYK8mpcnFTq9GsR2W0af/view?usp=sharing)
   
<!--* Query summary reports and distance matrices used for simulation experiment with overlapping contaminants:
    - [Dros_contam_overlap_k35_conf0.0.zip](https://github.com/noraracht/kraken_raw_data/blob/master/Dros_contam_overlap_k35_conf0.0.zip)-->


<!--* Query summary reports and distance matrices used for simulation experiment with overlapping contaminants:
    - [Dros_contam_overlap_k35_conf0.0.zip](https://github.com/noraracht/kraken_raw_data/blob/master/Dros_contam_overlap_k35_conf0.0.zip)-->
    
<!--* archive:   tar -zcvf BacArcKraken_FPplants_kraken_conf0.00.tar.gz BacArcKraken_FPplants_kraken_conf0.00
      unarchive: tar -xvzf BacArcKraken_FPplants_kraken_conf0.00.tar.gz-->
