# hse21_hw3
HomeWork 3. Bioinformatics course

Ссылка на ноутбук в коллабе 1: https://colab.research.google.com/drive/1AvJfLS-Jz2gpTM8TweKjbZ9hyObwiOt5#scrollTo=b23N89JW4Eeg 
Ссылка на ноутбук в коллабе 2 (статистика): https://colab.research.google.com/drive/1ImQwgFKvasfDdv-KHnE4OusgbjAxcR8u 

## Выравнивание RNA-seq чтений на геном мыши
### Отчет по multiqc
![General statistics](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/general_statistics.PNG)
![Seq counts](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/seq_counts.PNG)
![Quality hist](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/quality_hist.PNG)
![Quality scores](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/quality_scores.PNG)
![Content1](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/perBase_seq_content.PNG)
![GC content](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/gc_content.PNG)
![Duplication](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/duplications.PNG)
### Файлы hisat
![hisat file](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/hisat1.PNG)
![hisat file](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/hisat2.PNG)
### Общее число чтений, соответствующих хотя бы одному гену (для 6-ти образцов)
![greps](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/greps.PNG)
![counts](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/sum_count_reads.PNG)
### Вид таблицы ALL.counts - [https://github.com/kseniashilova/hse21_hw3/blob/main/data/ALL.counts]
![all counts](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/all_counts.PNG)
### Дополнительный файл ALL.info
![all info](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/all_info.PNG)

## Поиск генов, которые значимо поменяли свою экспрессию
### MA-plot
![MAplot](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/MA.png)
### Тепловая карта, которая показывает, что все контрольные образцы похожи между собой, а перепрограммированные образцы -- между собой
![heatmap](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/heatmap.png)
![heatmap2](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/heatmap2.png)
### Для нескольких генов, которые наиболее значимо поменяли свою экспрессию -- графики со значениями "Normalized counts" в контрольных и перепрограммированных образцах
![norm counts 1](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/norm_counts1.png)
![norm counts 1](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/norm_counts2.png)
![norm counts 1](https://github.com/kseniashilova/hse21_hw3/blob/main/pictures/norm_counts3.png)
