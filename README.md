# Double Vision: 2D and 3D Mosquito Trajectories can be as Valuable for Behaviour Analysis via Machine Learning

## About the project

Mosquitoes act as disease vectors, thus demanding a comprehensive understanding of their behaviour for effective disease control strategies. Tracking mosquitoes is an approach to gain insights into their movement. However, tracking systems vary in their complexity and scope of the data produced; from single camera setups giving 2-component data to stereoscopic, multi-camera and holographic techniques giving fully 3-dimensional information. The type of tracking system remains largely unexplored in the context of mosquito tracking. This paper presents a study where a dataset of 3D trajectories was used to determine the equivalent 2D data via telecentric imaging and single camera information at various imaging distances. Thereby, the performance of the tracking systems was assessed through an established machine learning classifier that attempts to differentiate male and non-male mosquito tracks, as well as analysis of trajectory feature values. The results reveal notable differences between the different imaging approaches used to track mosquitoes. Both telecentric and single camera models, when placed at large distances from the flying mosquitoes, demonstrate the potential to track flying mosquitoes effectively as well as preserving data integrity without resorting to more computationally intensive 3D tracking techniques. Caution should be exercised when employing a single camera model at short distances as the 3D orthogonal components of position become combined into a 2-component position vector owing to perspective geometry. Our findings indicate that trajectory features obtained in such scenarios significantly deviated from the other datasets, leading to reduced classification performance. Consequently, researchers should be mindful of this limitation when choosing the imaging approach to track mosquito or insect behaviour. Through this study, researchers can make informed decisions regarding tracking system selection as well as providing a path for more efficient and cost-effective mosquito behaviour studies.


## Usage

Install dependencies:
```
pip install -r requirements.txt
```

The main pipeline can be found in `main.ipynb`
