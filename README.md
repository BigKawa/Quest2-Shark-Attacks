# Quest2-Shark-Attacks
 Shark-Attacks

# slides
https://docs.google.com/presentation/d/1ffOLEdsFhuFjwfYm-IKGeflxyXxzx5IARtpaP6XQiTk/edit?usp=sharing

EDA Shark Attacks

#   Column          Non-Null Count  Dtype  
---  ------          --------------  -----  
 0   Date            6944 non-null   object 
 1   Year            6942 non-null   float64
 2   Type            6926 non-null   object 
 3   Country         6894 non-null   object 
 4   State           6462 non-null   object 
 5   Location        6379 non-null   object 
 6   Activity        6358 non-null   object 
 7   Name            6724 non-null   object
 8   Sex             6365 non-null   object 
 9   Age             3950 non-null   object 
 10  Injury          6909 non-null   object 
 11  Unnamed: 11     6382 non-null   object 
 12  Time            3418 non-null   object 
 13  Species         3812 non-null   object 
 14  Source          6925 non-null   object 
 15  pdf             6799 non-null   object 
 16  href formula    6819 non-null   object 
 17  href            6796 non-null   object 
 18  Case Number     6798 non-null   object 
 19  Case Number.1   6797 non-null   object 
 20  original order  6799 non-null   float64
 21  Unnamed: 21     1 non-null      object 
 22  Unnamed: 22     2 non-null      object 
dtypes: float64(2), object(21)

Notes on Columns

---
"Dates" 
Different formats, '15 Mar 2024' / '1883-1889' / nan / "0"
---
"Year"
Just three weird values
---
"Type"
Unprovoked', ' Provoked', 'Provoked', 'Questionable', 'Watercraft', 'Sea Disaster', nan, '?', 'Unconfirmed', 'Unverified', 'Invalid', 'Under investigation', 'Boat'
---
"Country"
Country name USA not unified, some NaN values
---
"Location"
Some numbers and NaN values instead of city/location names
---
"Activity"

---
"Name"
A wild mix of different attributes
---
"Sex"
Mostly M anf F, rest can probably be deleted
---
"Age"
Some ranges and words, mostly numbers of ages though
---
"Activity"
