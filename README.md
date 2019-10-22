# GermansFoodPreferences

The project was created during the subject *Computational Social Science* at *Koblenz University*.
Part of the data was provided by the teacher, the other part was scrapped from [kochbar.de](https://www.kochbar.de/).

## Hints for other team members
### Scrapper

1. Split file using method from scrapper/FileSplitter.ipynb
- Don't forget to change a path
- You should launch cells that are required

2. Scrapp categories from webpage using scrapper/CategoriesScrapperV2.ipynb
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

### Plots

#### Settings

1. Create an account on plot.ly and get credentials
2. In main folder create a text file named plotly_config.txt that looks like this

```bash
<my_username>;<my_api_key>
```

3. Don't commit this file
