# searchExactMatch
Aided with appropriated data (enumerated dict), search and locate exact matched content


Wallqty


Wallqty – dict_flipper

Flip over the entire dict, where value convert as the key over the entire nested dict. Key act as a value in number.


Wallqty – iter_func

Upon found key in dict match with specific item, dig out the value that matched item number from the flipped dict.


Wallqty – compose_new_dict

Uses the found item number to properly compile the extracted value into new dict that enumerated newly.


Wallqty – qty_list

Compile the extracted quantity that matches the search item into a list of quantities


Wallqty, conclusion

Taken from the laundry data, where data source is now all dict and enumerated. First flip the dict as value to key, key to value, to enable use of match function to search keyword. Upon finding keyword, then uses iter_func to determine the correct number of those matched item. Then compose them into a new list. Lastly, summing up the value of the list.
