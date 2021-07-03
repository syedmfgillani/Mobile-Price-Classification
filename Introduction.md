# Mobile Price Classification Project Introduction
Purpose of this project is to see how different tangible features of a mobile phone affect its price. The dataset containing detailed attributes for mobile phones was obtained from the website Kaggle. Kaggle is an online platform that, among other things, allows users to find and publish datasets, participate in data science competitions, and publish their work. It is owned by Google LLC. The present dataset was published by Abhishek Sharma in 2018, but no mention is done as to where the original dataset is sourced from.
The dataset contains information on 21 attributes for 2000 different mobile phone models. The attributes are as follows:
- Battery_power: how much energy can be stored in the battery of the mobile phone, measured in mAh.
- Blue: whether the mobile phone as bluetooth or not.
- Clock_speed: speed at which microprocessor executes instructions.
- Dual_sim: whether the mobile phone has dual sim support or not.
- Fc: definition of the front camera, measured in mega pixels.
- Four_g: whether the mobile phone has 4G or not
- Int_memory: internal memory, measured in Gigabytes.
- M_dep: mobile depth, measured in cm.
- Mobile_wt: weight of the mobile phone, measured in grams.
- N_cores: number of cores of processor.
- Pc: definition of the primary camera, measured in mega pixels.
- Px_height: pixel resolution height.
- Px_width: pixel resolution width.
- Ram: Random Access Memory, measured in Mega Bytes.
- Sc_h: screen height of the mobile phone, measured in cm.
- Sc_w: screen width of the mobile phone, measured in cm.
- Talk_time: longest time that a single battery charge will last when you are on call.
- Three_g: whether the mobile phone has 3G or not.
- Touch_screen: whether the mobile phone has touch screen or not.
- Wifi: whether the mobile phone has wifi or not.
- Price_range: this is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).

Price column in the data database contained categorical data as the price were divided into four ranges. The purpose of this work is to see which features of a mobile phone impact its price the most, and then compare different classification models to see which one performs better for this dataset. I used three models, i.e. Random Forest, Decision Tree, and Logistic Regression. Python is used as the main coding language in this project.   
