# hse_hw3_chromhmm
IPNB: https://colab.research.google.com/drive/12qhfcVECwhARH3SQxrk0UaPUB0atZuVI?usp=sharing
|Label | File name|
|----- | ------|
|Контроль | Control.bam|
|H3K27ac | H3k27ac.bam|
|H3K27me3 | H3k27me3.bam|
|H3K36me3 | H3k36me3.bam|
|H3K4me1 | H3k04me1.bam|
|H3K4me2 | H3k4me2.bam|
|H3K4me3 | H3k4me3.bam|
|H3K79me2 | H3k79me2.bam|
|H3K9ac | H3k9ac.bam|
|H3K9me3 | H3k09me3.bam|
|H4K20me1 | H4k20me1.bam|
|H2AFZ | H2az.bam|

|Type|Characteristic labels|Comment|
|----|-----|-----|
|1	| Enhancer	| H3K4me2, H3K4me3, H3K9ac, H3K27ac, H2AFZ|  |
|2	| Promoter	| H3K4me2, H3K4me1, H3K27ac, H2AFZ|  |	
|3	| Enhancer	| H3K4me1, H3K4me2|   |	
|4	| Transcribed / Gene bodies	| H3K79me2, H3K4me2, H3K4me1, H3K4me3|   |	
|5	| Transcribed / Intron	| H3K79me2, H3K36me3, H4K20me1||
|6	| Heterochromatin	| H4K20me1, H3K79me2, H3K36me3 (все - слабо) |	Покрывает 11% генома|
|7	| Heterochromatin	| H4K20me1 (слабо) |	Покрывает 69% генома|
|8	| Heterochromatin	| H3K9me3, H4K20me1	| Встречается очень редко, на стыках 6 и 7|
|9	| Heterochromatin	| H3K27me3, H4K20me1|   |
|10	| Transcribed / Gene bodies	| H3K36me3, H4K20me1|	  |
