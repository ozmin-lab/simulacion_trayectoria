# Proyecto de Graduación: "Simulación de Trayectoria" 🎈

Proyecto realizado por Osmin Larreynaga con asesoria de Ms. Napoleón Cornejo. 

Se crea una simulación de trayectoria ascendete y descendete de un globo-sonda a 30 Km, analizandose diferentes parámetros a lo largo de su recorrido.

## Estructura del Proyecto 📦
(ESTO SE IRÁ MODIFICANDO A MEDIDA AVANCE EL PROYECTO, ES SOLAMENTE UNA BUENA IDEA DE LA ESTRUCTURA)

    ├── LICENSE.txt
    ├── README.md           **<- La guía del proyecto.**
    ├── data_generate_from_model
    │   ├── README.md
    │   └── variables.csv
    ├── docs                **<- Referencias Bibliográficas.**
    │   └── us-standard-atmosphere_st76-1562_noaa.pdf
    ├── img
    │   └── FasesDeVueloMission_StratoBalloon.png
    ├── notebooks           **<- Jupyter Notebooks con cálculos.**
    │   ├── EDA.ipynb
    │   ├── Red Neuronal_TAC.ipynb
    │   ├── balloon.ipynb
    │   └── modelo.ipynb
    ├── requirements.txt    **<- Librerías del proyecto.**
    └── scripts_functions

## Proceso de Instalación ⚙️
![](https://thumbs.gfycat.com/UglyEminentEidolonhelvum-size_restricted.gif)

1. Clonar repositorio
``` bash
git clone <linK o SSH> && cd <directorio>
```
También se puede [descargar como archivo.zip aquí](https://github.com/ozmin-lab/simulacion_trayectoria/archive/refs/heads/main.zip "descargar en archivo.zip aquí") y descomprimirlo.

2. Crear ambiente virtual para ejecutar el programa
En Windows con WSL, Linux y Mac:
``` bash
python3 -m venv venv && source venv/bin/activate
```

3. Instalar las librerías contenidas en requirements.txt
``` bash
pip install -r requirements.txt
```

4. Todo Listo ya se trabajar en lo que necesites
