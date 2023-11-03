# data-versioning

This site is made to get an overview and actual tooling for data versioning. We are working on more subsites with tested toolings to provide more information.
We decided on using jupyter notebooks for the testing process, due to the broad usage options of jupyter notebooks in data analytics, which is probably the primary usage of data versioning.

### Testing process

- initialize repo 
- train a model on initial data (base model)
- commit model into main: data, model, and model parameters
- create a new branch (update branch)
- update data and train/retrain model (extra datapoints, deleted data points, and updated datapoints, to provoke merge conflicts)
- commit to update branch
- merge new data into the main branch

### Evaluation:

- Difficulty to set up (One sentence summary, any problems?)
- Detail of the documentation (Discoverability, Search for advanced issues)
- Git-like? (push/pull, commit, add, etc.)
- merge options (replace, update, etc.)
