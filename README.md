# Modeling Earthquake Damage


![picture1]()

*Intro Picture Source: photographer, unsplash.com*


## Introduction
I'm trying to predict the ordinal variable "damage_grade", which represents a level of damage to the building that was hit by the earthquake. There are 3 grades of the damage:

1 represents low damage
2 represents a medium amount of damage
3 represents almost complete destruction


## README Outline
* Introduction 
* README Outline
* Repo Contents
* Libraries and Prerequisites
* Feature and Definitions
* Models
* Conclusions
* Future Work
* Built With, Contributors, Authors, Acknowledgments


![picture2]()

*. Source: , Unsplash.com*


## Repo Contents
This repo contains the following:
* README.md - this is where you are now!
* Modeling_Earthquake_Damage.ipynb - the Jupyter Notebook containing the finalized code for this project.
* LICENSE.md - the required license information.
* Data - test.csv and train.csv files
* CONTRIBUTING.md 
* Images - contains the fun images to this repo.



## Libraries & Prerequisites
These are the libraries that I used in this project.

* import pandas as pd
* import numpy as np
* import matplotlib.pyplot as plt
* %matplotlib inline
* import seaborn as sns



## Features
There are 39 columns in this dataset, where the building_id column is a unique and random identifier. The remaining 38 features are described in the section below. Categorical variables have been obfuscated random lowercase ascii characters. The appearance of the same character in distinct columns does not imply the same original value.

Columns
* geo_level_1_id, geo_level_2_id, geo_level_3_id (type: int): geographic region in which building exists, from largest (level 1) to most specific sub-region (level 3). Possible values: level 1: 0-30, level 2: 0-1427, level 3: 0-12567.
* count_floors_pre_eq (type: int): number of floors in the building before the earthquake.
* age (type: int): age of the building in years.
* area_percentage (type: int): normalized area of the building footprint.
* height_percentage (type: int): normalized height of the building footprint.
* land_surface_condition (type: categorical): surface condition of the land where the building was built. Possible values: n, o, t.
* foundation_type (type: categorical): type of foundation used while building. Possible values: h, i, r, u, w.
* roof_type (type: categorical): type of roof used while building. Possible values: n, q, x.
* ground_floor_type (type: categorical): type of the ground floor. Possible values: f, m, v, x, z.
* other_floor_type (type: categorical): type of constructions used in higher than the ground floors (except of roof). Possible values: j, q, s, x.
* position (type: categorical): position of the building. Possible values: j, o, s, t.
* plan_configuration (type: categorical): building plan configuration. Possible values: a, c, d, f, m, n, o, q, s, u.
* has_superstructure_adobe_mud (type: binary): flag variable that indicates if the superstructure was made of Adobe/Mud.
* has_superstructure_mud_mortar_stone (type: binary): flag variable that indicates if the superstructure was made of Mud Mortar - Stone.
* has_superstructure_stone_flag (type: binary): flag variable that indicates if the superstructure was made of Stone.
* has_superstructure_cement_mortar_stone (type: binary): flag variable that indicates if the superstructure was made of Cement Mortar - Stone.
* has_superstructure_mud_mortar_brick (type: binary): flag variable that indicates if the superstructure was made of Mud Mortar - Brick.
* has_superstructure_cement_mortar_brick (type: binary): flag variable that indicates if the superstructure was made of Cement Mortar - Brick.
* has_superstructure_timber (type: binary): flag variable that indicates if the superstructure was made of Timber.
* has_superstructure_bamboo (type: binary): flag variable that indicates if the superstructure was made of Bamboo.
* has_superstructure_rc_non_engineered (type: binary): flag variable that indicates if the superstructure was made of non-engineered reinforced concrete.
* has_superstructure_rc_engineered (type: binary): flag variable that indicates if the superstructure was made of engineered reinforced concrete.
* has_superstructure_other (type: binary): flag variable that indicates if the superstructure was made of any other material.
* legal_ownership_status (type: categorical): legal ownership status of the land where building was built. Possible values: a, r, v, w.
* count_families (type: int): number of families that live in the building.
* has_secondary_use (type: binary): flag variable that indicates if the building was used for any secondary purpose.
* has_secondary_use_agriculture (type: binary): flag variable that indicates if the building was used for agricultural purposes.
* has_secondary_use_hotel (type: binary): flag variable that indicates if the building was used as a hotel.
* has_secondary_use_rental (type: binary): flag variable that indicates if the building was used for rental purposes.
* has_secondary_use_institution (type: binary): flag variable that indicates if the building was used as a location of any institution.
* has_secondary_use_school (type: binary): flag variable that indicates if the building was used as a school.
* has_secondary_use_industry (type: binary): flag variable that indicates if the building was used for industrial purposes.
* has_secondary_use_health_post (type: binary): flag variable that indicates if the building was used as a health post.
* has_secondary_use_gov_office (type: binary): flag variable that indicates if the building was used fas a government office.
* has_secondary_use_use_police (type: binary): flag variable that indicates if the building was used as a police station.
* has_secondary_use_other (type: binary): flag variable that indicates if the building was secondarily used for other purposes.


## Models



## Conclusions


![Picture3]()

**


## Future Work



![Picture4]()

* ! Source: , unsplash.com*


## Built With:
Jupyter Notebook
Python 3.0
scikit.learn


## Contributing
Please read CONTRIBUTING.md for details


## Authors
Thomas Whipple


## License
Please read LICENSE.md for details


## Acknowledgments
Thank you to DivenData for the fun competition and interesting data:
https://www.drivendata.org/competitions/57/nepal-earthquake/page/134/

