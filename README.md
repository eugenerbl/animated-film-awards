# Animated Film Awards
A database of five major awards for animated films, including nominees, winners, and film studios.
Data covers films released from 1991-2024

## Database Contents
* master_list.csv - A complete list of all films that have been nominated for at least one of the awards mentioned below.
* annie.csv - Nominees and winners for the Annie Award for Best Animated Feature and Best Animated Feature Film - Independent.
* bafta.csv - Nominees and winners for the BAFTA Award for Best Animated Film.
* globe.csv - Nominees and winners for the Golden Globe Award for Best Animated Feature Film.
* oscar.csv - Nominees and winners for the Academy Award (Oscar) for Best Animated Feature.

## Variable Definitions

### master-list.csv
* *year* - year of the film's U.S. release
* *oscar*, *globe*, *bafta*, *annie*, *annie_ind* - result of the film for the corresponding awards:
  * 0 - film was not nominated
  * 1 - film was nominated, but did not win
  * 2 - film was nominated and won award

### annie.csv, bafta.csv, globe.csv, oscar.csv
* In these files, *year* refers to the year of films recognized by the awards ceremony, not the year the actual ceremony was held.


## License

Distributed under the MIT License. See `LICENSE.txt` for more information.
