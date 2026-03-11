# 🥕 Multidimensional Postharvest Quality Analysis in Carrots  
### Spectral Techniques, Colorimetry & Artificial Intelligence

This repository contains the computational workflows and analysis scripts used in the study:

**“Multidimensional characterization of postharvest quality in carrot genotypes by temporal analysis of physicochemical, biofunctional, spectral and sensory parameters.”**

The analyses integrate **spectral techniques, colorimetry, physicochemical measurements, biofunctional assays, and consumer perception analysis** to understand how carrot quality evolves during storage.

The research evaluates **five carrot genotypes under two storage conditions (ambient and refrigeration)** across a **four-week postharvest period**, combining:

- Spectral reflectance analysis (Vis/NIR)
- Multivariate statistical modeling
- Consumer perception analysis
- Carotenoid quantification
- Machine learning–based classification approaches

The goal is to develop **non-destructive monitoring strategies for postharvest quality**, enabling predictive modeling of nutritional degradation and sensory acceptance.

---

# 📁 Repository Structure

## Spectral Signature Analysis (Temporal Monitoring)

Files:

- `OCT_09_cluster_firma_espectral.ipynb`
- `OCT_16_cluster_firma_espectral.ipynb`
- `OCT_23_cluster_firma_espectral.ipynb`
- `OCT_30_cluster_firma_espectral.ipynb`

These notebooks analyze the **temporal evolution of spectral signatures across four weeks of storage**.

Each notebook corresponds to a **sampling date** and performs:

- Spectral preprocessing  
- Reflectance curve analysis  
- Clustering of spectral responses  
- Identification of spectral patterns related to quality degradation  

The analyses are divided into **four experimental sections**:

1. Ambient storage – external surface measurement  
2. Refrigerated storage – external surface measurement  
3. Ambient storage – internal cross-section measurement  
4. Refrigerated storage – internal cross-section measurement  

This design allows tracking **how spectral signatures evolve over time depending on tissue exposure and storage temperature**.

---

## Multivariate Analysis & Spectral Indices

File:

`FIRMAS_MULTIVARIADO.ipynb`

This notebook performs **multivariate statistical analysis integrating spectral and physicochemical variables**.

Analyses include:

- **Linear Discriminant Analysis (LDA)** for genotype classification  
- Temporal comparison of spectral indices  
- Evaluation of spectral behavior across treatments  

The analysis is also structured into four sections:

- Ambient – external measurements  
- Refrigeration – external measurements  
- Ambient – internal measurements  
- Refrigeration – internal measurements  

This allows evaluation of **how spectral indicators evolve across storage conditions and tissue exposure**.

---

## Consumer Perception Analysis

File:

`ENCUESTAS_PERCEPCION.ipynb`

This notebook analyzes **consumer perception of carrot quality** based on survey responses.

The analysis includes:

- Natural Language Processing (NLP)  
- Word cloud visualization of consumer descriptors  
- Sentiment analysis of textual responses  

Consumers evaluated **five carrot varieties** subjected to two storage treatments:

- Ambient storage  
- Refrigerated storage  

This component links **instrumental quality measurements with consumer sensory perception**.

---

## Carotenoid Content Analysis

File:

`Carotenoides_zanahoria.ipynb`

This notebook analyzes the **temporal degradation of carotenoids during storage**.

The workflow includes:

- Processing absorbance data from spectrophotometric measurements  
- Estimation of **β-carotene concentration**  
- Temporal modeling of carotenoid degradation  

The analysis evaluates how **nutritional quality changes over time under different storage conditions**.

---

# 🧪 Experimental Design

- **5 carrot genotypes**
- **2 storage treatments**
  - Ambient temperature  
  - Refrigeration  
- **4 weeks of monitoring**
- **External and internal spectral measurements**
- **Consumer sensory evaluation**

This multidimensional approach integrates:

- Physicochemical measurements  
- Spectral signatures  
- Biofunctional compounds  
- Consumer perception  

---

# 📜 Citation and Responsible Use

Anyone using the datasets, models, scripts, or methodologies from this repository must cite:

### The SGR Project

**“Strengthening the Carrot Production Chain”**  
SGR Project — **BPIN 2020000100192**

### The Corresponding Scientific Article

Citation will be added upon publication.

---

⭐ **Provisional Citation**

Predictive Modeling of Carotenoid Content and Damage Classification in Carrots Using Spectral Techniques, Colorimetry, and Artificial Intelligence.  
SGR Project **BPIN 2020000100192**

---

# 📚 Acronym Dictionary

## Analytical Techniques

| Acronym | Meaning |
|------|------|
| Vis/NIR | Visible / Near Infrared Spectroscopy |
| NLP | Natural Language Processing |

---

## Spectral Indices

| Acronym | Meaning |
|------|------|
| NDVI | Normalized Difference Vegetation Index |
| CRI1 | Carotenoid Reflectance Index 1 |
| CRI2 | Carotenoid Reflectance Index 2 |
| mARI | Modified Anthocyanin Reflectance Index |

---

## Statistical Methods

| Acronym | Meaning |
|------|------|
| PCA | Principal Component Analysis |
| LDA | Linear Discriminant Analysis |

---

## Experimental Terms

| Acronym | Meaning |
|------|------|
| SGR | General Royalties System (Colombia) |
| BPIN | National Public Investment Project Code |

---

# 🔬 Research Context

This repository was developed within the framework of the **SGR-funded research project**:

**“Strengthening the Carrot Production Chain through the Development of Innovative Products in Eastern Antioquia.”**

Project Code: **BPIN 2020000100192**

The project integrates **spectroscopy, plant physiology, data science, and artificial intelligence** to improve **quality monitoring and postharvest management in carrot production systems**.
