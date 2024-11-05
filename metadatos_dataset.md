# Metadatos del Dataset

## Información General
Número de muestras: 140
Número de metabolitos: 149

## Resumen del Objeto
```
class: SummarizedExperiment 
dim: 140 149 
metadata(0):
assays(1): counts
rownames(140): sample_1 sample_2 ... sample_139 sample_140
rowData names(4): Idx SampleID SampleType Class
colnames(149): M1 M2 ... M148 M149
colData names(5): Idx Name Label Perc_missing QC_RSD
```

## Metadatos de las Muestras
```
DataFrame with 6 rows and 4 columns
               Idx    SampleID  SampleType       Class
         <numeric> <character> <character> <character>
sample_1         1    sample_1          QC          QC
sample_2         2    sample_2      Sample          GC
sample_3         3    sample_3      Sample          BN
sample_4         4    sample_4      Sample          HE
sample_5         5    sample_5      Sample          GC
sample_6         6    sample_6      Sample          BN
```

## Metadatos de los Metabolitos
```
DataFrame with 6 rows and 5 columns
         Idx        Name                  Label Perc_missing    QC_RSD
   <numeric> <character>            <character>    <numeric> <numeric>
M1         1          M1      1_3-Dimethylurate    11.428571  32.20800
M2         2          M2 1_6-Anhydro-β-D-gluc..     0.714286  31.17803
M3         3          M3   1_7-Dimethylxanthine     5.000000  34.99060
M4         4          M4   1-Methylnicotinamide     8.571429  12.80420
M5         5          M5         2-Aminoadipate     1.428571   9.37266
M6         6          M6        2-Aminobutyrate     5.000000  46.97715
```
