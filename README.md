Sketch JSON Parser
=================
#### Replaces layer values in groups with JSON data

### Setup
1. Download/Clone this repo
2. Run json-parser.sketchplugin

### Example
#####1. Say you have a group that looks like this:
![Layer Group Example](http://i.imgur.com/wKPFRdu.png)

#####2. And a JSON array that looks like this:
```
[{
    "img": "http://i.imgur.com/IBZMRic.png",
    "title": "Holabila",
    "date": {
        "formatted": "25 Jan 2015",
        "time_ago": "5 min ago"
    },
    "name": "Koen Vendrik"
},
{
    "img": "/Users/joeytribbiani/Desktop/350.png",
    "title": "Bilahola",
    "date": {
        "formatted": "28 Feb 2015",
        "time_ago": "2 days ago"
    },
    "name": "Jaer Pollux"
}]
```

#####3. Now include JSON path variables in your layer names like this:
![Path Variables Example](http://i.imgur.com/JsnUwv2.png)

#####4. Duplicate the group as many times as you want and select the groups
(in this case probably two times as you have two items in the array)

#####5. Run the plugin and paste in the JSON when prompted
![Prompt](http://i.imgur.com/sO4JCwi.png)

#####6. Voila! The plugin replaced all layer values with data from the JSON
![Woah GIF](http://www.reactiongifs.com/wp-content/gallery/omg/RDJ_Woah.gif)
