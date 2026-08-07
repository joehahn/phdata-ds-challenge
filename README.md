# phData data science challenge

Joe Hahn · jmh.datasciences@gmail.com

Who should this client be calling? Three notebooks, a client deck, and an agenda for the
technical session.

| file | what it is |
|---|---|
| `01_exploration.ipynb` | data exploration, cleansing, and the train/test split |
| `02_modeling.ipynb` | two models, tuning, metrics, feature importance |
| `03_business_value.ipynb` | what the model is worth on a real campaign budget |
| `business_deck.pptx` | the business-facing presentation |
| `technical_agenda.pdf` | agenda for the technical readout |
| `project_data.csv` | the data as delivered |

The notebooks are saved with their outputs, so they can be read without running anything.
To re-run, go in order: notebook 1 writes the parquets that notebook 2 reads, notebook 2
writes the model that notebook 3 reads. Notebook 2 takes about a minute, the other two
are seconds. Needs pandas, scikit-learn, seaborn, pyarrow and joblib.

I used an AI coding assistant throughout. All of the code is in the notebooks — nothing
is hidden in a module.
