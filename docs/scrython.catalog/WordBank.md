# **class** `scrython.catalog.WordBank()`

These docs will likely not be as detailed as the official Scryfall Documentation, and you should reference that for more information.

>In the event that a key isn't found or has been changed, you can access the full JSON output with the `scryfallJson` variable (`WordBank().scryfallJson`).

## Args

|arg|type|description|
|:---:|:---:|:---:|

## Returns
N/A

## Raises
N/A

## Examples
```python
>>> catalog = scrython.catalog.WordBank() 
>>> catalog.data() 
```

## Methods

---
### `data()`

```
A list of all types returned by the endpoint
        
        Returns:
            list
        
```
---
### `object()`

```
Returns the type of object it is
        (card, error, etc)
        
        Returns:
            string
        
```
---
### `total_values()`

```
The number of items in `data()`
        
        Returns:
            integer
        
```
---
### `uri()`

```
The API URI for the endpoint you've called.
        
        Returns:
            string
        
```