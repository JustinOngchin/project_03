# project_03

The `ebay.dl` file converts eBay searches into a list, in either a `.json` or `.csv` file. These files include the `name` of the item, the `price` of the item, the `status` of the item (i.e. Brand New or Used), the price of `shipping`, whether the item has `free_returns`, and the number of `items_sold`.

To run the python file, use the following command line:
```
$ python3 ebay-dl.py 'SEARCH TERM'
```
where `'SEARCH TERM'` is the desired item to look for on EBay. When performing searches with multiple words, use quotations so that the terminal does not treat it as two separate arguments. 

This file also includes two options: `--num_pages` and `--csv`. `--num_pages` is used as the following:
```
$ python3 ebay-dl.py 'SEARCH TERM' --num_pages=X
```
where `X` can be replaced by the number of pages you want, with a default value of 10 pages.

`--csv` is used as the following:
```
$ python3 ebay-dl.py 'SEARCH TERM' --csv
```
By default, `ebay-dl.py` will produce a compilation of items in a `.json` format. By including the `--csv` tag, the file will instead produce a `.csv` file instead.

For instructions on thie project, click [here](https://github.com/mikeizbicki/cmc-csci040/tree/2022fall/project_03).