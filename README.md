# model-enrichment

**BPI Challenge 2016 Customer Support Log**: Original log for the customers who logged in and asked at least one question from top 10 subthemes is created by integrating different files from https://www.win.tue.nl/bpi/doku.php?id=2016:challenge. The original log is available at this link due to its big size: https://drive.google.com/drive/folders/1ciCIQYFwtafksrwEl_uOx1UMLJ44A4Zq?usp=sharing

**bpi_variants.csv**: File with manually generated paraphrases/variants of the original questions asked in original file.

**BPI_original_gt.zip**: Ground truth and predicted keyphrase for unique questions present in 10 subthemes.

**bpi_variant_gt.zip**: Ground truth and predicted keyphrase for unique questions including manually added paraphrases, present in 10 subthemes.

**bpi_original_mapping.zip**: Mapping of predicted and ground truth keyphrases for original questions to avoid spurious penalty on metrics.

**bpi_variant_mapping.zip**: Mapping of predicted and ground truth keyphrases for questions with paraphrases to avoid spurious penalty on metrics.

**tree_visualization_original.zip**: Contains two files: *bpi_original_tree.json* and *tree_visualization_bpi_original.html*. Please download this folder and open HTML file using Chrome to render interactive hierarchical tree visualization capturing keyphrase and comment relationship for BPI original questions data.

**tree_visualization_variant.zip**: Contains two files: *bpi_variants_tree.json* and *tree_visualization_bpi_variant.html*. Please download this folder and open HTML file using Chrome to render interactive hierarchical tree visualization capturing keyphrase and comment relationship for BPI variant questions data. Can notice that the paraphrases are mostly grouped under same keyphrases highlighting the value of keyphrase extraction-annotation approach.

**Enriched BPI Challenge 2016 Customer Support Log**: The enriched log is available at given link due to its big size: https://drive.google.com/drive/folders/1ciCIQYFwtafksrwEl_uOx1UMLJ44A4Zq?usp=sharing
