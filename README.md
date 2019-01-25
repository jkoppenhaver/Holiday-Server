# Holiday-Server
## Holiday Format
The following format can be used to add new holidays to the end of the list.
````
<day of the year>:{  
    "name":<Name of Holiday>,
    "colors":[  
      <List of color strings in hex prefixed by a pound sign>
    ],
    "Variable":<boolean representing if date of the year can change from year to year>
  }

Example:
"45":{  
    "name":"Valentine's Day",
    "colors":[  
      "#5E081E",
      "#E24767",
      "#FFFFFF"
    ],
    "Variable":"False"
  }
````
