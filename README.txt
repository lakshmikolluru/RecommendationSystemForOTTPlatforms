---- README ----
The datasets for Netflix, Amazon Prime, Hulu, Disney+,
IMDB Review dataset were downloaded from Kaggle and
the links to the original dataset are included in
the report.

The file 'Dataset Preprocessing Part 1.html' consists of
the following actions:
- Data cleaning is performed on the 4 datasets Netflix,
  Amazon Prime, Hulu, Disney+.
- These 4 datasets are merged into 1 single dataset.
  This is saved into 'all_titles_original.csv' file 
  (which is not present in this folder).

Once 'all_titles_original.csv' file is created, we've
been extracting data from the IMDB API. The scripts
used for extracting data from the API are 'Getting User
Ratings From IMDB API Part 1.html'. Once all the
directors and actors have been extracted from the API,
the updated dataframe is saved as 'all_titles.csv'
(which is present in this folder and we'll be using
this data file for the rest of the project).

'Getting User Ratings From IMDB API Part 1.html' and
'Getting User Ratings From IMDB API Part 2.html' 
contains scripts for extracting User ratings. These
ratings are saved into 3 files 'imdb_api_part_1.csv',
'imdb_api_part_2.csv' and 'imdb_api_part_3.csv' (which
is not present in this folder).

'Dataset Preprocessing Part 2.html' consists of the 
following actions:
- All the IMDB datasets (1 downloaded from Kaggle
  and 3 csv files with data extracted from API) are
  merged into 1 file.
- Data cleaning and transformation is done as required.
- The merged dataset is saved as 'user_ratings.csv' 
  (which is present in this folder and we'll also be
  using this data file for the rest of the project).
- 'user_ratings.csv' is split into user_ratings.csv and 
  'user_ratings2.csv' files because memory constraints 
   of github.

* After the execution of the above mentioned scripts
(Jupyter notebooks), we've saved these scripts as
'.html' version. Running these scripts again might
replace the data we've acquired so far.

* We'll only be only using 'all_titles.csv' and 
'user_ratings.csv' data files for the rest of the project.

The remaining code for the rest of the project is
present in 'Recommendation System.ipynb'.
