# Double Vision: 2D and 3D Mosquito Trajectories can be as Valuable for Behaviour Analysis via Machine Learning

## Abstract

Mosquitoes are carriers of tropical diseases, thus demanding a comprehensive understanding of their behaviour to devise effective disease control strategies. In this paper we show that machine learning can provide a performance assessment of 2D and 3D machine vision techniques and thereby guide entomologists towards appropriate experimental approaches for behaviour assessment.  Behaviours are best characterised via tracking – giving a full time series of information.  However, tracking systems vary in complexity.  Single camera imaging yields 2-component position data which generally are a function of all 3 orthogonal components due to perspective, however, a telecentric imaging setup gives constant magnification with respect to depth and thereby measures two orthogonal position components.  Multi-camera or holographic techniques quantify all 3 components.  In this study a 3D mosquito mating swarm dataset was used to generate equivalent 2D data via telecentric imaging and a single camera at various imaging distances. The performance of the tracking systems were assessed through an established machine learning classifier that differentiates male and non-male mosquito tracks. SHAPs analysis has been used to explore the trajectory feature values for each model. The results reveal that both telecentric and single camera models, when placed at large distances from the flying mosquitoes, can produce equivalent accuracy from a classifier as well as preserving characteristic features without resorting to more complex 3D tracking techniques. Caution should be exercised when employing a single camera at short distances as classifier balanced accuracy is reduced compared to that from 3D or telecentric imaging; the trajectory features also deviate compared to those from the other datasets. It is postulated that measurement of two orthogonal motion components is necessary to optimise the accuracy of machine learning classifiers based on trajectory data. The study increases the evidence base for using machine learning to determine behaviours from insect trajectory data. 


## Usage

Install dependencies:
```
pip install -r requirements.txt
```

The main pipeline can be found in `main.ipynb`
