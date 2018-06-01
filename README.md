> var sherdog = require('sherdog');
> var url = "http://www.sherdog.com/fighter/Khumoyun Ibragimov"
> sherdog.getFighter(url, function(data) {
    console.log(data);
  })
> {
    "name": "Khumoyun Ibragimov",
    "nickname": "TAMERLAN",
    "age": "23",
    "birthday": "1994-08-28",
    "locality": "ISTANBUL,",
    "nationality": "UZBEKISTAN",
    "association": "Throwdown",
    "height": "6'2\"",
    "weight": "155 lbs",
    "weight_class": "lightweight",
    "wins": {
        "total": 0,
        "knockouts":0,
        "submissions": 0,
        "decisions": 0,
        "others": 0
    },
    "losses": {
        "total": 0,
        "knockouts": 0,
        "submissions": 0,
        "decisions": 0,
        "others": 0
    },
    "no_contests": 0,
    "fights": [
        }
        // ... 
    ]
  }
