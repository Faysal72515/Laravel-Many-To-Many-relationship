# Laravel-Many-To-Many-relationship-
Laravel Many To Many relationship between categories and products table

1. How to create a Pivot table in Laravel

  1.1 The name of the pivot table should consist of singular names of both tables, separated by underscore symbols, and these names should be arranged in alphabetical order, so we have to have category_product, not product_category.
   1.2 To create a pivot table, we can create the simple migration with artisan make:migration....
  1.3 Pivot table fields: by default, there should be only two fields – the foreign key to each table, in our case category_id and product_id. You can insert more fields if you need, then you need to add them to the relationship assignment.
  
    following link:  https://appdividend.com/2022/01/21/laravel-many-to-many-relationship/
