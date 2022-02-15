Page 1
List of city
> http://localhost:6700/location
> https://zomatonodeapi.herokuapp.com/location
List of restaurants 
> http://localhost:6700/restaurants
> https://zomatonodeapi.herokuapp.com/restaurants
restaurants wrt to city 
> http://localhost:6700/restaurants?state_id=4
> https://zomatonodeapi.herokuapp.com/restaurant?stateId=1
quick search data  
> http://localhost:6700/mealType
> https://zomatonodeapi.herokuapp.com/mealType

(http://localhost:6700/restaurants?state_id=4&meal_id=5)
https://zomatonodeapi.herokuapp.com/restaurants?state_id=4&meal_id=5

Page 2
restaurants wrt to quickSearch 
> http://localhost:6700/restaurants?meal_id=5
>https://zomatonodeapi.herokuapp.com/restaurants?meal_id=5


filter
> cuisine filter
  data respect to cuisine and quickSearch 
  > http://localhost:6700/filter/3?cuisine=4
  > https://zomatonodeapi.herokuapp.com/filter/3?cuisine=4
> cost filter
  > http://localhost:6700/filter/1?lcost=200&hcost=500
  > https://zomatonodeapi.herokuapp.com/filter/1?lcost=200&hcost=500
 data respect to cuisine and cost 
> cuisine filter + cost filter 
  > http://localhost:6700/filter/1?lcost=200&hcost=500&cuisineId=1
  >https://zomatonodeapi.herokuapp.com/filter/1?lcost=200&hcost=500&cuisineId=1

> sort
    sort low to high in same quickSearch
    http://localhost:6700/filter/1?cuisineId=1&sort=1
    sort high to low in same quickSearch
    http://localhost:6700/filter/1?cuisineId=1&sort=-1

> pagination
   > http://localhost:6700/filter/1?cuisineId=1&skip=2&limit=2
   >https://zomatonodeapi.herokuapp.com/filter/1?cuisineId=1&skip=2&limit=2


Page 3
> restaurants details
> http://localhost:6700/details/2
> https://zomatonodeapi.herokuapp.com/details/2

> Menu of that restaurants
> http://localhost:6700/menu/2
> https://zomatonodeapi.herokuapp.com/menu/1


page 4
> menu items on user selection
  > localhost:6700/menuItem
  > https://zomatonodeapi.herokuapp.com/menuItem
  > body [1,4,5]

> api to place order
  > localhost:6700/placeOrder

page 5
> list all order
  > http://localhost:6700/orders
  >https://zomatonodeapi.herokuapp.com/orders
  > http://localhost:6700/orders?email=""

Delete order 
> localhost:6700/deleteOrder
 

 update order
 > localhost:6700/updateOrder/620bac3ee33c06217632b6e7?status=success