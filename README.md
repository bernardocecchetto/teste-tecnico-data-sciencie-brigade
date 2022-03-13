# teste-tecnico-data-sciencie-brigade
The following repository contains all the analysis and conclusions about the tecnical test from Data Science Brigade. 

The Jupyter Notebook file named "analysis.ipynb" contains a lot of analisys about the patterns of purchases from the public organs of RS state, separing these patterns by year and organs, to analyze how much was spent, with what was spent, when was spent, and some other explanations about the results obtained.

It was used Python language and the following frameworks for the analysis:
- Pandas
- Matplotlib
- Numpy


# Instructions:

## Dataset used
The files used in following study comes from:
- https://drive.google.com/file/d/1OfxA4FGzR4zOy8KIdPl8cAK5ojsJv-vV/view
- https://drive.google.com/file/d/1OfxA4FGzR4zOy8KIdPl8cAK5ojsJv-vV/view
- https://drive.google.com/file/d/1FEGbEIhE3WQrkd3iy20b5fBi2xwbakXL/view
- https://drive.google.com/file/d/1NGpVRqo9xbvEUSzR9KWOOf4V6GeBc5a7/view

And it was downloaded the files named as "item.csv" and "licitacao.csv" from each link, which represents different years, and they was named as following:
- "name_of_the_file-" + "year_of_the_data.csv"

In files that is named like "item-" + "year_of_the_data.csv" has data about the items that was bought by public organs from the RS state.
In files that is named like "licitacao-" + "year_of_the_data.csv" has data about the licitations of the items that was bought by public organs from the RS state.

## How to download directly the named files
Please, to download the data used for the following analysis, download it from https://drive.google.com/drive/folders/1KYo5dtau-zmCrLK5rYieAt_i0HqJoPxP?usp=sharing and put it in the project folder. Just like that:

- teste-tecnico-data-sciencie-brigade
  - data
    - item
      - item-2016.csv
      - item-2017.csv
      - item-2018.csv
      - item-2019.csv
    - licitacao
      - licitacao-2016.csv
      - licitacao-2017.csv
      - licitacao-2018.csv
      - licitacao-2019.csv

  - analisys.ipynb  

Or you can just, in the code, change the folder that the data will be loaded. Please, any difficult, contact to cecchetto.bernardo@gmail.com.

## How to reproduce the virtual environment used
To reproduce the virtual environment that was used, please just create a virtual environment, install the pip package and install the packages in the file "requirements.txt" using the follow command:

pip install -r requirements.txt


