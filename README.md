# PROG6221FINALPOE
Final part of prog6221 poe
WPF display.

brings in the required namespaces.

defines the application window's representation, the MainWindow class.

contains all recipes stored in a private List<Recipe> variable named allRecipes.

brings about the InitializeRecipes() function and initialises the MainWindow class.

carries out the UpdateRecipeList() function:

filteredRecipes is an IEnumerable<Recipe> variable that is created and originally set to allRecipes.

confirms that the ingredientTextBox is not empty before filtering the recipes according to the inputted ingredient.

verifies if a food group is chosen from the foodGroupComboBox and then applies a filter to the recipes according to the chosen group.
