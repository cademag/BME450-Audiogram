# BME450-Audiogram
# Hearing Loss Classification via Audiogram

## Team members
- Cade Magnuson (cademag) <br/>
- Pablo Torres (torrespj)
## Project decription
In this project, we aim to develop a machine learning model that can classify the type of hearing loss (normal, conductive, or sensorineural) based on audiogram data. Accurate identification of hearing loss type is essential in clinical audiology for selecting the appropriate treatment path. We will utilize a publicly available dataset from Kaggle tittled "Audiogram Analysis for Tinnitus Detection" (https://www.kaggle.com/datasets/kavehmcsd/audiogram-analysis-for-tinnitus-detection/data), which includes air conduction and bone conduction hearing thresholds accross various frequencies for patients with normal hearing and those diagnosed with conductive or sensorineural hearing loss.  
The primary goal of this project is to build and evaluate a machine learning model (using both traditional algorithms and deep learning architectures) to automatically and accurately differentiate between the types of hearing loss based on audiogram features. This will involve feature extraction, preprocessing, model training, and performance evaluation. The final outcome will not serve as a classification tool but as a foundation for future development of automated audiological diagnostic aids. 

## Data Import
cd path/to/BME450-Audiogram
mkdir -p data/images
cp /path/to/your/jpg/files/*.jpg data/images/
ls data/images/
git add data/images/
git commit -m "Add audiogram JPG image files"
git push origin main
