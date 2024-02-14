# 🍺 Angular Beer Shop Gallery🍺

This is a demo project to create a beer shop gallery and practice with Angular framework and signals specifically.

![image](https://github.com/pacoita/ng-beer-shop/assets/13237093/401da4ed-acd0-488f-b6ce-2a31d84df7c0)


## Structure

There are two folders:

- **start:** containing the initial code fresh out of an `ng new` command, nothing more. This is the starting point for the exercise.

- **final:** contains a possible solution and can be accessed in case you are blocked with your implementation.

## Requirements

- The main page shows a list of available beers (fetched from the Punk IPA API: https://api.punkapi.com/v2/beers)
- Each beer can be toggled as a favorite 
- The no. of favorite beers must be tracked in the UI
- From 5 favorite beers, shipping cost is for free (update the label text accordingly)
- Reactivity should be implemented using Angular Signals
 
Pro requirement 🚀 (optional)
- Set a random price for each beer item (this is not provided by the API) and add a drop-down for the order quantity. It should be possible to select the number of beers to order for each item
 and add them to the cart via an icon (just the final price in the header is enough). The total amount of the selected beers should be displayed in the header.

The DTO Model for the beer items can be the following (there are many other fields returned from the API that can be skipped for the sake of simplicity).

```typescript
interface BeerItem  {
   name: string
   first_brewed: string
   description: string
   image_url: string
   abv: number
   ibu: number
  }
```
