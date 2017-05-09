<div align="center">
Powered by [Vue](https://vuejs.org) **2.0** & [Bulma](http://bulma.io) **0.3**
</div>

# Grocery Store Monopoly Checker

Simple JavaScript page to check your game pieces against the rare piece list. [Try it!](http://peltedvenom.com/grocery_store_monopoly/)

Type in the three key characters. For example: if you have the pice **8B99D** then type in `8bd` or `8BD`. The notice will turn green and stop input when a needed game piece has been entered. Otherwise it will continue on by clearing the input and letting you continue.

The current `rare_pieces.js` file includes the 2017 rare and semi-rare pieces. These are the ones that are hardest to acquire as they are only released in limited quantities based on the game rules.

You can also edit the `rare_pieces.js` file with any game piece numbers you need by inclduing them in the list.

## Current Rare Piece List

```javascript
{
  "8BD": "8B99D",
  "8BE": "8B00E",
  "8CA": "8C91A",
  "8CC": "8C93C",
  "8DA": "8D86A",
  "8DB": "8D87B",
  "8EB": "8E82B",
  "8EE": "8E85E",
  "8FA": "8F77A",
  "8GC": "8G75C",
  "8HD": "8H72D",
  "8JB": "8J66B",
  "8KD": "8K64D",
  "8LA": "8L57A",
  "8MB": "8M54B",
  "8NC": "8N51C",
  "8PC": "8P47C",
  "8QA": "8Q41A",
  "8RD": "8R40D",
  "8SB": "8S34B",
  "8TD": "8T32D",
  "8VC": "8V27C",
  "8WA": "8W21A",
  "8XB": "8X18B",
  "8YF": "8Y14F",
  "8YH": "8Y16H",
  "8ZG": "8Z07G",
  "8ZH": "8Z08H",
  "9AB": "9A03B",
  "9AC": "9A04C",
  "9BA": "9B07A",
  "9BD": "9B10D",
  "9CD": "9C15D",
  "9DA": "9D16A",
  "9EC": "9E22C",
  "9FC": "9F26C",
  "9GD": "9G31D",
  "9HA": "9H32A",
  "9JB": "9J37B"
}
```
