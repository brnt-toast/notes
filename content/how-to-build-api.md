# How to build an API

# Prep
* CRUD
* Event-Driven
* Hypermedia 

# Design
fleshing out the implementation and spinning up a prototype
### Resources
"Look at the terms in your application domain" -- [1]
> For example: A door may be a resource whereas color and door handle are its attributes, and open and close are the actions the door may afford. -- [1]

```json
{
    "house": {
        "resources" : {
            "door" : {
                "attributes": [
                    {"color":"red"},
                    "handle"
                    ],
                "actions" : ["open","close"]
            },
            "wall" : {
                "attributes" : {},
                "actions" : {},
            },
            "stairs" : {
                "attributes" : {},
                "actions" : {},
            },

        },
    }
}
```

## Resources
1. [apriary]('https://apiary.io/how-to-build-api')