# Chocolate-Ratings-Predictions
For the project, the dataset ‘chocolate.csv’ was taken from Kaggle.com. The cleaning of data was performed for each columns using descriptive statistics and exploratory data analysis. One of the columns from the dataset – specific_bean_origin was a very noisy column and cleaning for that column was done using Tokenization. For this, the external library ‘spacy’ was installed and used. Other columns were not as noisy, so tokenization was not employed. So, for other columns, we had used vectorization to clean.

Note: Installation Requirements

    Spacy: (for Named Entity Recognition for pre processing specific_bean_origin)
        pip install spacy
        python -m spacy download en_core_web_sm
    
    Plotly: (for mapping chocolate ratings across geographical location)
        pip install plotly
