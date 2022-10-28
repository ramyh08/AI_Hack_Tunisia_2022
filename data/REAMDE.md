## About

This is anonymised real data. The data looks at 54 different stores in the same country and 33 different products.

The train set contains transaction information for 3 years and 6 months. You are tasked with forecasting the next 8 weeks for the same stores and same products.

**NB: logp1 (log(x+1)) transformation was applied to the label on the testing set, hence we are asking you to apply the logp1 transformation on your predictions before making any submission.**

## Main variable definitions :

    Target: the total sales for a product category at a particular store at a given date
    Stores_id: the unique store id
    Category_id: the unique Product category id
    Date: date in numerical representation
    Onpromotion: gives the total number of items in a Product category that were being promoted at a store at a given date
    Nbr_of_transactions: the total number of transactions happened at a store at a given date
    year_weekofyear: the combination of the year and the week of the year, (year_weekofyear = year*100+week_of_year)
    ID: the unique identifier for each row in the testing set: year_week_{year_weekofyear}_{store_id}_{Category_id}

## Files :

| Description  | FILES |
| ------------- | ------------- |
| Resembles Train.csv but without the target-related columns. <br> This is the dataset on which you will apply your model to.  | Content Cell  |
| Information about holidays  | Content Cell  |
| Information about the different stores such as their locations ||
| Information about the time periods with their associated date features e.g. day of the week, day of the year, etc ||
| Shows the submission format for this competition, with the ‘ID’ column mirroring that of Test.csv. The order of the rows does not matter, but the names of the ‘ID’ must be correct. ||
| Contains the target. This is the dataset that you will use to train your model. ||
