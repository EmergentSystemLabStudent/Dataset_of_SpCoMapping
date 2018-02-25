# Dataset_of_SpCoMapping

### Overview  
This is the dataset used for SpCoMapping.

### Description
We used SIGVerse which is the simulation environment of the daily living environment.  
For each environment, we did three trials.

* `/map` : The occupied grid map for each environment.

* `/room*` : The dataset used for SpCoMapping
  * `/room*/img_*` : The directory including obtained image
  * `/room*/1_*.ppm` : The occupied grid map  
  The colored pixels means the robot obtained vocabularies on that pixel.
  * `/room*/2_*.ppm` : The occupied grid map  
  The colored pixels means the robot obtained image feature on that pixel.
  * `/room*/Ft.csv` : The list of image feature
  * `/room*/pose_*.csv` : The list of the robot's pose
  * `/room*/St.csv` : The list of vocabulary
  * `/room*/StXtx.csv` : The X coordinate which the robot obtained vocabulary
  * `/room*/StXty.csv` : The Y coordinate which the robot obtained vocabulary
  * `/room*/word_*.csv` : The list of vocabulary for each trial
  * `/room*/Xtx.csv` : The X coordinate which the robot obtained image feature
  * `/room*/Xty.csv` : The Y coordinate which the robot obtained image feature

### Install
`git clone https://github.com/EmergentSystemLabStudent/Dataset_of_SpCoMapping.git`
