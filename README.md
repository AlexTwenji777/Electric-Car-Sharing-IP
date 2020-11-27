# Electric Car Sharing Service IP
This is a repository for the Telcom IP carried out during my time in Moringa School on 27-11-2020
## Environment Used
* Google Colab
* Atom
* Terminal Command Line
## Technologies Used
* Python version 3
* Pandas Library
* Numpy Library
## Code Example
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline

Autolib_Check = Autolib.Cars == Autolib['Bluecar counter']

Autolib = pd.read_csv('Autolib_dataset (2).csv')

Bluecar = Autolib.drop(['Cars','Utilib counter','Utilib 1.4 counter','Displayed comment','ID','Kind','Geo point','Public name','Subscription status'], axis=1)

Bluecar.columns = Bluecar.columns.str.replace(' ', '_')
Autolib
## License
MIT © AlexTwenji777
