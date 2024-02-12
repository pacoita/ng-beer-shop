# 🍺 Angular Beer Shop Gallery🍺

This is a demo project to create a beer shop gallery and practice with Angular signals.

## Structure

There are two folders:

- **start:** containing the initial code fresh out of a `ng new` command, nothign more. This is the starting point for the exercise.

- **final:** contains a possible solution and can be accessed in case you are blocked with your implementation.

## Requirements

- The main page shows a list of available beers (fetched from the Punk IPA API: https://api.punkapi.com/v2/beers)
- Each beer can be toggled as favorite 
- The no. of favourite beers must be tracked in the UI
- From 5 favorite beers, shipping cost is for free (update the label text accordingly)
 
Pro requirement 🚀 (optional)
- Set a random price to each beer item (this is not provided by teh API) and add a drop down for the order quantity. It should be possible to select the number of beers to order for each item
 and add them to the cart via icon (just the final price in the header is enough). The total amount of the selected beers should be displayed in the header.

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
