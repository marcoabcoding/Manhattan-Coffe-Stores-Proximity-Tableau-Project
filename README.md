## Coffee Proximity Analysis
This project analyzes the locations of Megabucks Coffee Company stores in Manhattan, NYC. The goal is to assist in identifying potential new store locations to ensure customers are always within a ½ mile of an existing store. This is part of the company's vision to optimize store coverage and enhance customer convenience.


### Store Proximity Analysis:

A self-join was performed on the store dataset to calculate the distance between each store, excluding comparisons of the same store IDs.
Great Circle Distance Formula was used to calculate the distances between stores as a calculated field.

### Visual Representation:

A map was generated to represent each store's location.
The size of the  shapes indicates the distance to the nearest other stores.

### Gap Identification:

Stores more than ½ mile apart were highlighted to reveal areas that are underserved.
This led to the identification of five potential gaps where new stores could be opened to enhance coverage and reduce customer distance from stores.

![Captura de tela 2024-10-08 175345](https://github.com/user-attachments/assets/c5d45d87-04d4-4588-83b4-0db3f0376163)
