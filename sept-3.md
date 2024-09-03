#### Datasets and Tabular Data 
- For our purposes, we'll usually want data in tabular form. This corresponds to a table in a relational database, but more generically we call it a dataset. When using the Python library Pandas, you may also see it referred to as a dataframe. 
- Let's load a dataset in Weka, then view the dataset in tabular form by using the “edit” button. We'll start with the Pima Indian Diabetes dataset and then the Iris dataset. 
- Each row is a data point, aka as instance, object, observation, record, or case. 
- Each column is a feature, aka as attribute, variable, field, or characteristic. 
- Let's use the “edit” button in Weka to view the data in tabular form.

**wekka call the target, the class**
In the diabetes dataset there are two classes tested positive or tested negative
#### Classification
- Categorical Targets 

#### Data Types 
- Note how each feature has a data type. In Weka, the data types used are nominal and numeric. 
- Each feature in our Weka dataset will be one of these types.  
- The basic data types we'll be working with, at least at first, are categorical, numeric, and binary. 
- Categorical data is often further subdivided into ordinal and nominal data types. Ordinal data types have an order (e.g. danger levels of “low”, medium”, and “high”) while nominal don't. In Weka, both are treated as nominal by default. 
- Numeric data is sometimes further defined as continuous or discrete and interval or ratio. We will leave those distinctions to a later time.