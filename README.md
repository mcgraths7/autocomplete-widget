# autocomplete-widget

A reusable autocomplete widget

## How to use

There are six items that are required in the configuration object that gets passed

### root

The root element to insert the autocomplete widget into

### renderOption

How to display each option returned by fetchData

### inputValue

What to display in the input box when an autocomplete option is selected

### fetchData

An API call which returns the requested data, handle errors as needed in here

### typeOfData

A string which tells the widget what to label the input

### onOptionSelect

A callback function which takes in the individual data item, and does something with it
