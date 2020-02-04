# data!
| | Method |species| N datasets|gene list|spot table| cell x gene | notes|
| ----: | ---- | ---- | ---- | ---- | ---- | --- | --- |
| 1 |DARTFISH| *M. musculus*| | [DARTFISH_genes](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/DARTFISH_genes.csv)|[SpotTable Human 1](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/DARTFISH/DARTFISH_DecodedSpots_Hs_FCtx_20180122.csv) [SpotTable Human 2](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/DARTFISH/DARTFISH_DecodedSpots_Hs_OCtx_20180122.csv),  [SpotTable Mouse 1](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/DARTFISH/DARTFISH_DecodedSpots_Mm_20190513.csv)|[CellxGene Human 1](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/DARTFISH/DARTFISH_CellxGene_Hs_FCtx_20180122_T.csv),  [CellxGene Human 2](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/DARTFISH/DARTFISH_CellxGene_Hs_OCtx_20180122_T.csv) [CellxGene Mouse 1](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/DARTFISH/DARTFISH_CellxGene_Mm_20190513_T.csv)
| 2 |MERFISH (Zhuang: MOp) | *M. musculus*| | [MERFISH_genes](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/MERFISH_genes.csv)|  | [file with S3 locations (Mouse, primary motor cortex)](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/MERFISH_zhuang_lab_MOp/file_list.csv) 
| 3 |osmFISH| *M. musculus*| | [osmFISH_inhibitory_genes](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/osmFISH_inhibitory_genes.csv), [osmFISH_excitatory_genes](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/osmFISH_excitatory_genes.csv)|[SpotTable Mouse Excitatory 0](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/osmfish/osmFISH_counts_excitatory_roi_0.csv),  [SpotTable Mouse Excitatory 1](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/osmfish/osmFISH_counts_excitatory_roi_1.csv), [SpotTable Mouse Inhibitory 0](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/osmfish/osmFISH_counts_inhibitory_roi_0.csv), [SpotTable Mouse Inhibitory 1](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/osmfish/osmFISH_counts_inhibitory_roi_1.csv)|
| 4 |BARISTASeq| *M. musculus*| | [BARISTASeq_genes](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/BARISTASEQ_genes.csv)|[SpotTable Mouse](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/BARISTASEQ/all_spots.csv)|[CellxGene Mouse](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/BARISTASEQ/cell_by_gene.csv)
| 5 |ISS| *M. musculus*| | [ISS_genes](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/ISS_genes.csv)|[SpotTable Mouse 1](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/ISS/ISS_1_spot_table.csv) [SpotTable Mouse 2](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/ISS/ISS_2_spot_table.csv) [SpotTable Mouse 3](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/ISS/ISS_3_spot_table.csv)|
| 6 |ExSeq| *M. musculus*| | [ExSeq](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/exseq_genes.csv)||[CellxGene Table mouse](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/ExSeq/cellxgene.csv)||*...working on it...*
| 7 |SeqFISH| *M. musculus*| | [SeqFISH](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/seqfish_genes.csv)|||*...working on it...*
| 8 |MERFISH (Allen: VISp, same panel as Zhuang lab above) | *M. musculus*| | [MERFISH_genes](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/MERFISH_genes.csv)|[SpotTable Mouse VISp](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/MERFISH_Allen_VISp/spot_table.csv)|[CellxGene Mouse VISp](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/MERFISH_Allen_VISp/1001844875_2_output_dataframe.csv)
|9|Allen smFISH VISp, (spacejam1)|*M. musculus*||[smfish_genes](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/smFISH_Allen/gene_list.csv)|[SpotTable Mouse VISp](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/smFISH_Allen/smFISH_MCT_CZI_Panel_0_spot_table.csv)||[nucleus segmentation (geojson)](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/smFISH_Allen/SongLinROIS_deduplicated.json)
|10|10x-Visium/ST| *M. musculus*|n/a|n/a|[observation x gene table 1](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/spatial-transcriptomics-alma/Allen-1-count-matrix.tsv.gz), [observation x gene table 2](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/spatial-transcriptomics-alma/Allen-2-count-matrix.tsv.gz), [observation x gene table 3](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/spatial-transcriptomics-alma/Allen-3-count-matrix.tsv.gz), [observation x gene table 4](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/spatial-transcriptomics-alma/Allen-4-count-matrix.tsv.gz)||*each file is a gzipped tsv*


***



[**THIS SPREADSHEET**](https://docs.google.com/spreadsheets/d/1CN7kn8ELg9dhVPDkeb7JB02NYYTNUEqfaKkO40yWDzM/edit?usp=sharing) contains links to all the data and many of the analyses from the first spacejam, including the **RNA-seq reference data and consensus clusters**.  Several of these files are shared in the "spacetx" slack workspace.  Please ask [Jeremy](mailto:jeremym@alleninstitute.org) to invite you if needed, or if you have any questions about data access for things in this table.
