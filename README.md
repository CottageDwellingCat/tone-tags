# tone-tags
Popular tone-tags in a easy to use json format for inclusion in your projects
## Contributing
Feel free to add your own tonetags by making a pr, if you disagree with a tags inclusion or aliases please make an issue; however if you notice tonetags that don't follow the naming conventions outlined below you can update them without making an issue. You can also open a pr to show off your cool tone-tag friendly project below.
## Format
```jsonc
{
    // Easy to read tag name, Capitalize all words and use 
    // hyphens instead of spaces
    "DefaultName": "Not-Forcing",
    // Recognisable short alias for a tag, this should
    // be 3 or less characters in most cases and should 
    // be the most commonly used version of the tag (eg /gen)
    "DefaultShortName": "nf", 
    // A description of the tags meaning. Try to keep it 
    // under two sentences unless additional verbosity is needed.
    "Description": "Shows that a statement or request is a suggestion, and the person does not want you to feel obliged to complete it.",
    // These should be the full words that the tag represents. 
    // Casing isn't important but spaces should still be hyphenated
    "Aliases": [
        "not-forcing",
        "nForcing"
    ],
    // These should be short versions of the tags name 
    // (eg. /j instead of /joking)
    "ShortAliases": [
        "nf"
    ],
    // If you found the tag somewhere else on the internet 
    // link to the cardd / site / tumblr post, if it was 
    // somewhere private (like a discord server or dm) 
    // use your internet name™️ and link to yourself.
    "Source": {
        "Title": "CottageDwellingCat",
        "Url": "https://github.com/CottageDwellingCat/"
    }
},
```
# Projects
## [Mewdeko](https://github.com/Pusheon/Mewdeko)
Mewdeko is a discord bot that supports resolving the tonetags in a message with a single right click and searching for tonetags to help you find the perfect one.
![image](https://user-images.githubusercontent.com/80918250/204075434-4f45833d-c550-41ec-9b2b-a437e840e604.png)
![image](https://user-images.githubusercontent.com/80918250/204075480-09dda21a-08a8-4038-a968-d2f5596acc8f.png)
