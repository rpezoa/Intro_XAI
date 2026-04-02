# Introducción a la IA Explicable

¡Bienvenidos al repositorio **Intro_XAI**! 🎓 Este repositorio contiene ejercicios diseñados para actividades prácticas en temas de **IX Explicable**.

## Setup local

### Requisitos previos
- Python 3.11 ([pyenv](https://github.com/pyenv/pyenv) recomendado: `pyenv install 3.11.9`)
- Jupyter Notebook o VS Code con extension Jupyter

### Crear entorno virtual

```bash
# Crear venv con Python 3.11
python3.11 -m venv .venv

# Activar
source .venv/bin/activate        # Linux/macOS
# .venv\Scripts\activate         # Windows

# Instalar dependencias
pip install -r requirements.txt

# Registrar kernel para Jupyter
python -m ipykernel install --user --name xai-env --display-name "Python (XAI)"
```

Al abrir un notebook, seleccionar el kernel **Python (XAI)**.

### Notas
- Algunos notebooks descargan datos y modelos desde Google Drive con `gdown`. Requiere conexion a internet en la primera ejecucion.
- Los notebooks con `from google.colab import drive` estan pensados para Google Colab. En ejecucion local, esas celdas deben comentarse o adaptarse.
- El notebook `12_Spectral_Lines_v0.ipynb` usa `tensorflow-addons` (descontinuado). Puede requerir ajustes para funcionar localmente.

## Estructura del repositorio

### **1. Notebooks**
Jupyter notebooks interactivos que abordan diversos temas.



| Núm.  | Tema  | Link  |
|----------|----------|----------|
| 0   | Intro: Uso de Jupyter Notebooks   |   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/00_Events_Classification.ipynb) |
| 1    |  Modelo tranparente:  regresión lineal |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/01_Linear_Regression_Iris.ipynb)|
| 2    |  LIME Tabular  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/02_LIME-Datos-Tabulados.ipynb)  |
| 3    |  LIME Imagenes  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/02_LIME_Clasificación-Imágenes.ipynb)  |
| 4    |  KernelSHAP  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/04_SHAP_Kernel-Explainer-Higgs.ipynb)  | 
| 5    |  Counterfactual OmniXAI  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/05_Counterfactual_OmniXAI.ipynb)  |  
| 5    |  SHAP con TreeExplainer  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/04_SHAP_TreeExplainer.ipynb)  | 
| 6    |  Saliency Maps  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/06_Saliency_Maps.ipynb)  | 
| 7    |  CAM  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/07_CAM_LoadModel.ipynb)  | 
| 8    |  Grad-CAM  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/07-Grad_CAM.ipynb)  | 
| 9    |  Inferencia Variacional  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/09_VI_Linear_Regression.ipynb)  | 
| 10    | Regression y NLL  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/09_Linear_Regression_NN.ipynb)  | 
| 11    | Regression con MC Dropout  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rpezoa/Intro_XAI/blob/main/14_MC_Dropout_Pytorch.ipynb)  | 




## 🧑‍🏫 About

This repository is maintained by **Raquel Pezoa**. Feel free to reach out for questions, suggestions, or collaborations!
