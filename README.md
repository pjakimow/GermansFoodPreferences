# GermansFoodPreferences

## Content

### For Binder

- CategoriesAnalysis-Binder.ipynb. 
Modified *CategoriesAnalysis.ipynb* file for plotting via binder.

### Others

- scrapper/CategoriesScrapperV2.ipynb. 
Current version of categories scrapper.

- scrapper/FileSplitter.ipynb. 
Splits file into many small files. Used to split file for scrapping to more persons.

- scrapper/FileConnecter.ipynb. 
Connects many files into one file. Used after webscrapping. 

- ExploringData.ipynb. 
Contains some data exploring procedures. Checking the number of examples for each city/day. 

- DataPreparation.ipynb. 
Contains preparation of data before subsequent use. Season extraction, data unifying, duplicates removal. 

- FilePreparation.ipynb. 
Creates dictionaries with grouped data by city/season/both. Saves data to *file/to_plot* folder for subsequent use as base for plots.

- files/to_plot. 
Contains data created from log and scrapped data needed for plots.

- CategoriesAnalysis.ipynb. 
Reads files from *files/to_plot* and creates plots.

- HypothesisTesting.ipynb. 
Contains hypothesis testing.


## Scrapping

Last updated python file for scrapping is *scrapper\CategoriesScrapperV2.ipynb* 

### Steps for Scrapping

1. Split file using method from *scrapper/FileSplitter.ipynb*
- Don't forget to change a path
- You should launch cells that are required

2. Scrapp categories from webpage using *scrapper/CategoriesScrapperV2.ipynb*
- Don't forget to change a path to read from
- Parameter all_rows should be set to True

```bash
pathToRead = <?>
all_rows = True
```
- You can also change path to save if you want

```bash
pathToSave = <?>
```
- You should launch cells that are required

## Plots

Modified python file for plotting via binder is *CategoriesAnalysis-Binder.ipynb*
When not using Binder: *CategoriesAnalysis.ipynb*

### Settings

1. Create an account on *plot.ly* and get credentials
2. In main folder create a text file named *plotly_config.txt* that looks like this

```bash
<my_username>;<my_api_key>
```
3. Don't commit this file

### Note

The credentials can be already defined, but can be just temporaly valid.
