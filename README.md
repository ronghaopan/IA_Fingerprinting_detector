# IA_Fingerprinting_detector
Fingerprinting Detector IA es un herramienta basada en OpenWPM y inteligencia artifical que permite la detección de técnicas de extracción de huellas o fingerprinting activo. Se analiza un base de datos de un millon de sitios web publicados por la universidad Pricenton y se ha creado tres modelos de detección con una precesión de entorno 96%. 
## Requirements
### Operating System
Ubuntu version higher than 18.04 is recommended
### Dependencies
- OpenWPM (https://github.com/citp/OpenWPM). To install OpenWPM, I ran the install.sh script. If you want to develop the extension that OpenWPM uses to instrument or run tests specific to this tool, use the install-dev.sh script.
- Anaconda (Recommended) (https://docs.anaconda.com/anaconda/install/). Includes the Pandas and Jupyter Notebook packages.
- The application notebook is designed to run inside the same folder where OpenWPM is located.
