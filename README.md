# Recipe Book - simple web-app with Angular2 framework

App deployed to [https://levrun.github.io/recipes](https://levrun.github.io/recipes) via gh-pages

You can browse, add, edit, save your favorite recipes.
Also there's ability to add ingredients to shopping-list.
In the right-upper corner there's dropdown where you can store and upload
data from/to firebase db.

This app is a result of passing course from Udemy [https://www.udemy.com/the-complete-guide-to-angular-2](https://www.udemy.com/the-complete-guide-to-angular-2)
created by [Maximilian Schwarzmüller](https://www.udemy.com/user/maximilian-schwarzmuller/)

How to run
----------

* You should have *node* and *npm* installed
* You should have *angular-cli* installed
* Open project folder and run *ng init*
* After it you could run *ng-serve*
* And open [http://localhost:4200](http://localhost:4200) to check how app working

Libraries
---------
* TypeScript
* Angular2 2.2.1
* angular-cli 1.0.0-beta.21
* Webpack for build
* Firebase for backend storage
* Bootstrap and ng2-bootstrap module

Design
------
App divided into several components and modules:

* AppModule - main module with AppComponent, HeaderComponent
* CoreModule - DropdownDirective, HomeComponent
* ShoppingListModule - ShoppingListComponent, ShoppingListAddComponent
* SharedModule - just for the sake of showing how to share CommonModule to other modules
* RecipesModule - RecipesComponent, RecipeListComponent, RecipeItemComponent, RecipeDetailComponent, RecipeEditComponent, RecipeStartComponent
