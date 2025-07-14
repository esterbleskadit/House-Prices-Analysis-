# Column Names and descriptions for King County Data Set

- **id** - unique identified for a house
- **dateDate** - house was sold
- **pricePrice** - is prediction target
- **bedroomsNumber** - # of bedrooms
- **bathroomsNumber** - # of bathrooms
- **sqft_livingsquare** - footage of the home
- **sqft_lotsquare** - footage of the lot
- **floorsTotal** - floors (levels) in house
- **waterfront** - House which has a view to a waterfront
- **view** - quality of view
- **condition** - How good the condition is ( Overall )
- **grade** - overall grade given to the housing unit, based on King County grading system
- **sqft_above** - square footage of house apart from basement
- **sqft_basement** - square footage of the basement
- **yr_built** - Built Year
- **yr_renovated** - Year when house was renovated
- **zipcode** - zip
- **lat** - Latitude coordinate
- **long** - Longitude coordinate
- **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
- **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors


# Column Names and descriptions for King County Data Set
|Column|Description|my info
|---|---|---|
**id** | unique identified for a house | unique? False: 21420, True: 177
**dateDate** | house was sold | date √
**pricePrice** | is prediction target
**bedroomsNumber** | # of bedrooms | array([ 3,  2,  4,  5,  1,  6,  7,  8,  9, 11, 10, 33])
**bathroomsNumber** | # of bathrooms | 29 continous numbers. Why?!
**sqft_livingsquare** | footage of the home | int
**sqft_lotsquare** | footage of the lot | int
**floorsTotal** | floors (levels) in house | array([1. , 2. , 1.5, 3. , 2.5, 3.5])
**waterfront** | House which has a view to a waterfront | NaN!! array([nan,  0.,  1.]) -> True/False √
**view** | quality of view | array([ 0., nan,  3.,  4.,  2.,  1.])
**condition** | How good the condition is ( Overall ) | array([3, 5, 4, 1, 2])
**grade** | overall grade given to the housing unit, based on King County grading system| array([ 7,  6,  8, 11,  9,  5, 10, 12,  4,  3, 13])
**sqft_above** | square footage of house apart from basement | int
**sqft_basement** | square footage of the basement| NaN!! float -> calc new, int √
**yr_built** | Built Year | int -> date (year) ?
**yr_renovated** | Year when house was renovated | NaN! -> date (year) ?
**zipcode** | zip | int
**lat** | Latitude coordinate | useful?
**long** | Longitude coordinate | useful?
**sqft_living15** | The square footage of interior housing living space for the nearest 15 neighbors | int (do I need that?)
**sqft_lot15** | The square footage of the land lots of the nearest 15 neighbors | int (do I need that?)
sqft_above