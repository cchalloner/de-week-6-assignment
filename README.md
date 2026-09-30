# Week 6 Assignment: Reusable Shipment Prediction Workflow

Use the course virtual environment (.venv) that you already set up. Do not create another environment in this repository.

Open `Week_06_Assignment.ipynb` in VS Code and select the Python kernel from your existing course .venv. Read the workflow specification before coding. Complete each TODO, run the notebook from beginning to end, and leave the outputs visible. Save, commit, and push your work to the Classroom 50 repository.

The notebook reads `data/week6_assignment_shipments.csv`. Keep that file in the data folder. Do not rename or move it.

The notebook asks you to split the raw labeled rows before fitting, fit the Pipeline on the training rows only, and predict for the held-out test rows. You will compare test predictions with known delivery times. Separate future shipment rows have no known target and are used only to practice prediction with the fitted workflow.

Your finished notebook should show “All Week 6 assignment checks passed.” in the final verification cell. Include the short written responses in the notebook.
