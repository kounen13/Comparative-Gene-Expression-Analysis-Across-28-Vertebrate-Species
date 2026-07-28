# 🧬Comparative-Gene-Expression-Analysis-Across-28-Vertebrate-Species
## 📌 description

Comparative Gene Expression Analysis of 29 vertebrate species using Bgee seq data, 
comparative analysis of tissue-specific gene and its visualization by using R studio.


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
