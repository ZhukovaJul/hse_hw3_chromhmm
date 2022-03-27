# hse_hw3_chromhmm

<h3>Ссылка на google colab </h3> 
https://colab.research.google.com/drive/1FxWtlQeg7V4jmm-MotaNYoZBBfVQEr67?usp=sharing <br>

<h3>Гистоновыe метки</h3> 
H3K27aс: http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k27acAlnRep1.bam <br>
H2AFZ : http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H2azAlnRep1.bam <br> 
H3K36me3 : http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k36me3AlnRep1.bam <br>
H3K4me1 : http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k04me1AlnRep1.bam <br>
H3K4me2 : http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k04me2AlnRep1.bam  <br>
H3K4me3 : http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k04me3AlnRep1.bam <br>
H3K79me2 : http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k79me2AlnRep1.bam <br>
H3K9ac : http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k09acAlnRep1.bam  <br>
H3K9me3 : http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k09me3AlnRep1.bam  <br>
H4K20me1 : http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H4k20me1AlnRep1.bam <br>
Контроль : http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746ControlAlnRep1.bam <br>

<h3>Папка с выдачей ChromHMM - output</h3> 

<h3>Картинки из выдачи ChromHMM</h3> 

![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/a4d5cf021c87a3dbd8b05cafab3e5b32efd60a1d/output/Monocytes-CD14+_RO01746_10_RefSeqTES_neighborhood.png)
![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/a4d5cf021c87a3dbd8b05cafab3e5b32efd60a1d/output/Monocytes-CD14+_RO01746_10_RefSeqTSS_neighborhood.png)
![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/a4d5cf021c87a3dbd8b05cafab3e5b32efd60a1d/output/Monocytes-CD14+_RO01746_10_overlap.png)
![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/a4d5cf021c87a3dbd8b05cafab3e5b32efd60a1d/output/emissions_10.png)
![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/a4d5cf021c87a3dbd8b05cafab3e5b32efd60a1d/output/transitions_10.png)

<h3> Эпигенетических типы </h3>

| Номер  | Название | Описание | Изображение | 
|---|---|---|---|
| 1   | Transcribed | Встречается в H3k36me3. RefSeqTES/RefSeqGene/RefSeqExon. Малый сигнал |![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/5f671fc9a1ba2ee02b9a9126170f94e389aba89d/img/1.PNG)|
| 2   | Promoter | Встречается в H3k36me3,H3k79me2, H4k20me1. RefSeqTES/RefSeqGene/RefSeqExon. Высокий сигнал |![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/5f671fc9a1ba2ee02b9a9126170f94e389aba89d/img/2.PNG)|
| 3   | Transcribed | Встречается в H3k36me3,H3k79me2, H4k20me1. RefSeqGene. Малый согнал|![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/5f671fc9a1ba2ee02b9a9126170f94e389aba89d/img/3.PNG)|
| 4   | Enhancer | Встречается в H3k36me3,H3k79me2, H4k20me1. Меньше встречается в H3k4me1, H3k4me2. RefSeqGene. Высокий сигнал|![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/5f671fc9a1ba2ee02b9a9126170f94e389aba89d/img/4.PNG)|
| 5  | Enhancer  | Встречается в H3k4me1, H3k4me2, H3k79me2, H4k20me1. RefSeqGene. Высокий сигнал|![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/5f671fc9a1ba2ee02b9a9126170f94e389aba89d/img/5.PNG)|
| 6   | Heterochromatin | Встречается в H3k4me1, H3k4me2, H3k27ac. laminB1lads. Малый сигнал |![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/5f671fc9a1ba2ee02b9a9126170f94e389aba89d/img/6.PNG)|
| 7  | Promoter |Встречается в H3k4me1, H3k4me2, H3k4me3, H3k27ac. CpGIsland/RefSeqTSS/RefSeqExon/RefSeqTSS2kb. Высокий сигнал |![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/5f671fc9a1ba2ee02b9a9126170f94e389aba89d/img/7.PNG)|
| 8   | Heterochromatin | Встречается в H2az. laminB1lads. Малый сигнал |![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/5f671fc9a1ba2ee02b9a9126170f94e389aba89d/img/8.PNG)|
| 9   | Heterochromatin | Встречается в H2az, H3k4me2. laminB1lads. Малый сигнал |![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/5f671fc9a1ba2ee02b9a9126170f94e389aba89d/img/9.PNG)|
| 10   | Enhancer | Встречается в H3k9me3, H3k36me3,H3k79me2.  RefSeqTES/RefSeqExon. Средний сигнал  |![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/5f671fc9a1ba2ee02b9a9126170f94e389aba89d/img/10.PNG)|

<h3>Бонус </h3> 
![](https://github.com/ZhukovaJul/hse_hw3_chromhmm/blob/5f671fc9a1ba2ee02b9a9126170f94e389aba89d/img/bonus.PNG)

<h3>Список команд </h3> 

```!wget http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k27acAlnRep1.bam -O H3K27ac.bam 
!wget http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H2azAlnRep1.bam -O H2AFZ.bam  
!wget http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k36me3AlnRep1.bam -O H3K36me3.bam 
!wget http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k04me1AlnRep1.bam -O H3K4me1.bam 
!wget http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k04me2AlnRep1.bam -O H3K4me2.bam 
!wget http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k04me3AlnRep1.bam -O H3K4me3.bam 
!wget http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k79me2AlnRep1.bam -O H3K79me2.bam 
!wget http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k09acAlnRep1.bam -O H3K9ac.bam 
!wget http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H3k09me3AlnRep1.bam -O H3K9me3.bam 
!wget http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746H4k20me1AlnRep1.bam -O H4K20me1.bam
!wget http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneMonocd14ro1746ControlAlnRep1.bam -O control.bam 
!curl -O https://raw.githubusercontent.com/deepjavalibrary/d2l-java/master/tools/fix-colab-gpu.sh && bash fix-colab-gpu.sh 
!curl -O https://raw.githubusercontent.com/deepjavalibrary/d2l-java/master/tools/colab_build.sh && bash colab_build.sh 
!java --list-modules | grep "jdk.jshell" 
! wget http://compbio.mit.edu/ChromHMM/ChromHMM.zip 
!unzip /content/ChromHMM.zip 
!java -mx5000M -jar /content/ChromHMM/ChromHMM.jar BinarizeBam -b 200  /content/ChromHMM/CHROMSIZES/hg19.txt /content/ cellmarkfiletable.txt   binarizedData 
!java -mx1600m -jar /content/ChromHMM/ChromHMM.jar LearnModel -p 0 binarizedData output 10 hg19 
import pandas as pd
df = pd.read_csv('Monocytes-CD14+_RO01746_10_dense.bed', encoding='utf-8', sep='\t', comment='t', header=None)
header = ['chrom', 'chromStart', 'chromEnd', 'state', 'zero', 'dot', 'chromStart', 'chromEnd', 'rgb']
df.columns = header[:len(df.columns)]
df.loc[df.state == 1, 'state'] = '1_Transcribed'
df.loc[df.state == 2, 'state'] = '2_Promoter'
df.loc[df.state == 3, 'state'] = '3_Transcribed'
df.loc[df.state == 4, 'state'] = '4_Enhancer'
df.loc[df.state == 5, 'state'] = '5_Enhancer'
df.loc[df.state == 6, 'state'] = '6_Heterochromatin'
df.loc[df.state == 7, 'state'] = '7_Promoter'
df.loc[df.state == 8, 'state'] = '8_Heterochromatin'
df.loc[df.state == 9, 'state'] = '9_Heterochromatin'
df.loc[df.state == 10, 'state'] = '10_Enhancer'
df.to_csv('dense.bed', sep='\t', index=False, header=None)
```

