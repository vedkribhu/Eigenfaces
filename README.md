# Foobar

Foobar is a Python library for dealing with word pluralization.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
while all orders not specified:
    ## For Drones
    sort the orders according to start time
    find all the drones at rest:
          if drone at customer place:
                 return to nearest warehouse
          else:
                 greedily try to process orders
                 if it can satisfy order from top send there
    ## For Trucks
    for all rested trucks:
         if truck at manufacturing plant
                send it to nearest warehouse 
         else
                find the manufacturing plant which can satisfy maximum order
                 find the truck with max (W/d**0.5), w-> wt cap of truck, d-> dist 
         
   
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
