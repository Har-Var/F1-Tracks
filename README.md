# F1-Tracks

## Description  
This repo only contains the data files for the dashboard [F1-Tracks](https://public.tableau.com/app/profile/harshit/viz/F1Tracks/Formula1Tracks).

## Project Structure
The data is organized as follows:
* `data`: Contains all the data files.
  - `interim`: Folder for storing interim files.
      - `gpt-scrape.xlsx`: asked chatgpt to scrape from wikipedia
      - `kaggle-combined.xlsx`: combined relevant files from kaggle dataset 
      - `manual-scrape.xlsx`: manually obtained data from statsf1
      - `web-connect.xlsx`: fetched using excel web connector from multiple websites
  - `tableau`: Folder for storing final data files for Tableau.
      - `data.xlsx`: final data file for Tableau
      - `f1-circuits-normalized.geojson`: normalized spatial data file for Tableau


## Contributing
Contributions are welcome! If you have suggestions or improvements, please open a pull request.

## License
This project is licensed under the MIT License.

## Authors
- [Har-Var](https://github.com/Har-Var)

## Acknowledgments
The data was sourced from the following links:
- https://github.com/bacinger/f1-circuits/blob/master/f1-circuits.geojson
- https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020
- https://www.statsf1.com/
- https://en.wikipedia.org/wiki/List_of_Formula_One_circuits
- https://motorsporttickets.com/blog/lap-records-in-formula-1-list-fastest-lap-times-at-every-circuit/
- https://www.planetf1.com/tracks

