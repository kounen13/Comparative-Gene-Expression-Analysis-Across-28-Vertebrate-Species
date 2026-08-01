# 🧬Comparative-Gene-Expression-Analysis-Across-28-Vertebrate-Species And Low-TPM Gene Analysis in Domestic Cat
## 📌 description

Comparative Gene Expression Analysis of 29 vertebrate species using Bgee seq data, 
comparative analysis of tissue-specific gene and its visualization by using R studio. and finding highest no of low tpm genes across tisuue 


## 😼 Species used


```bash
- Felis catus (Domestic Cat)
- Homo sapiens (Human)
- Mus musculus (House Mouse)
- Canis lupus familiaris (Domestic Dog)
- Bos taurus (Domestic Cattle)
- Gallus gallus (Chicken)
- Equus caballus (Horse)
- Sus scrofa ( Pig)
- Ovis aries (Sheep)
- Capra hircus ( Goat)
- Rattus norvegicus (Norway Rat)
- Oryctolagus cuniculus (European Rabbit)
- Monodelphis domestica (Gray Short-tailed Opossum)
- Ornithorhynchus anatinus (Platypus)
- Pan troglodytes (Chimpanzee)
- Pan paniscus (Bonobo)
- Gorilla gorilla (Western Gorilla)
- Papio anubis (Olive Baboon)
- Macaca mulatta (Rhesus Macaque)
- Macaca nemestrina (Pig-tailed Macaque)
- Cercocebus atys (Sooty Mangabey)
- Chlorocebus sabaeus (Green Monkey)
- Callithrix jacchus (White-tufted-ear Marmoset)
- Heterocephalus glaber (Naked Mole-Rat)
- Cavia porcellus (Guinea Pig)
- Meleagris gallopavo (Turkey)
- Crab
```

## 🦋 Group

### group 1
```bash
chicken
mangabey
pig
platypus
turkey
white tuffed ear

```


### group 2
```bash
cat
cattle
dog
goat
horse
pig
sheep
```

### group 3
```bash
crab
gray mouse
guinea_pig
mole_rat
opposum_m
rabbit
rat
```

### group 4
```bash
human
baboon
chimpanzee
gorilla
green monkey
macaque_m
pan_paniscus
```

### more specific toward cat


## 📝** Data source.**


[![](https://img.shields.io/badge/Bgee-Database-green)](https://www.bgee.org/)[Bgee species data](https://www.bgee.org/search/species)

* Each dataset contain *
  ```bash
     1. Experiment ID

     2. Species

     3. Library ID

     4. Library type

     5. Gene ID

     6. Anatomical entity ID

     7. Anatomical entity name

     8. Stage ID

     9. Stage name

     10. Sex

     11. Strain

     12. Read count

     13. TPM

     14. Rank

     15. Detection flag

     16. pValue

     17. State in Bgee
  ```
     ## 🔃Process
  

     **-download rna-seq expression database from Bgee**
  
     **-merge multiple experiment dataset of same species into one dataset file**
  
     **-merge 7-species dataset into one pair**
  
     **-4 pair of species group created**
  
     **-perform all this process in R studio.**
  
     **-generated multiple plot using this dataset through R studio**

   ## 📊 visualization.

   ```bash
   1. Gene Count vs TPM Distribution
   2. TPM Distribution Boxplot
   3. TPM Distribution Violin Plot
   4. Read Count vs TPM Scatter Plot
   5. Median TPM Across Species
   6. Detection Flag Distribution
   7. Heatmap of Mean TPM by Species and Tissue
   8. Density Distribution of TPM Across Species
   9. Median TPM Lollipop Plot
   10. Bubble Plot of Mean TPM and Gene Count
   11. Gene Distribution Pie Chart
   12. Mean TPM Line Plot
   13. Expression Variability Box Plot

   ```

   ## 🧬 Low Gene Expression Analysis in Domestic Cat

  ### Objective

  To identify tissues containing the highest number of low-expression genes (TPM < 1) in the domestic cat transcriptome.

  ### 🔃 process
  -  Filtered all genes with TPM < 1.
  -  Grouped the filtered data by anatomical tissue.
  -  Counted the number of unique low-expression genes in each tissue.
  -  Compared tissues using a bar plot.
 
    ### Result



| Rank | Anatomical Tissue | Low-Expression Genes |
|:---:|----------------------------|--------------------:|
| 1 | Liver | 23,968 |
| 2 | Skeletal muscle tissue | 23,482 |
| 3 | Heart | 22,948 |
| 4 | Adult mammalian kidney | 22,482 |
| 5 | Spleen | 22,457 |
| 6 | Lung | 20,111 |
| 7 | Adipose tissue | 19,483 |
| 8 | Hindlimb muscle | 19,386 |
| 9 | Brain | 18,116 |
| 10 | Testis | 14,045 |
| 11 | Embryo | 8,755 |
| 12 | Tip of external ear | 7,622 |
| 13 | Prefrontal cortex | 7,181 |
| 14 | Zone of skin | 7,106 |
| 15 | Eyeball of camera-type eye | 6,615 |
| 16 | Uterus | 6,197 |
| 17 | Embryonic head | 5,669 |


## visualization (bar plot).

![bar plot](https://github.com/kounen13/Comparative-Gene-Expression-Analysis-Across-28-Vertebrate-Species/blob/main/cat/low_tpm/Screenshot%202026-07-29%20024644.png?raw=true)

### 📝 conclusion 
Low-expression gene analysis (TPM < 1) revealed clear differences among cat tissues. The
liver exhibited the highest number of low-expression genes (23,968), whereas the embryonic
head had the fewest (5,669). These results demonstrate that the abundance of lowly expressed
genes varies across tissues
