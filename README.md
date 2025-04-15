Crime Rate Prediction Using Big Data and Machine Learning
As part of my postgraduate coursework in Big Data and Cloud Computing, I developed a data-driven platform to analyze and forecast crime trends in the UK using a combination of Apache Spark, Pandas, and machine learning models. The system processed over 19 million rows of street-level crime data obtained from the UK Home Office.

The initial phase involved distributed data preprocessing using PySpark on an Azure VM, followed by exploratory data analysis and visualization using Pandas, Matplotlib, and Seaborn. Key visualizations included pie charts, trend graphs, and heatmaps highlighting violent crime hotspots and regional risk levels.

To forecast future crime rates, I implemented ARIMA-based time series models using the statsmodels library. These models analyzed multi-year crime patterns and provided actionable insights into rising or declining trends. For example, firearm-related incidents in Liverpool were shown to be consistently above average compared to other major UK cities.

While the ARIMA model showed promising results in capturing seasonality and overall trend patterns, areas for enhancement included integrating more diverse crime datasets (e.g., socioeconomic or weather data), exploring deep learning-based forecasting, and refining model parameters for improved F1 score and RMSE.

The project demonstrates how big data technologies and predictive modeling can support law enforcement, urban planning, and insurance risk assessment by identifying and anticipating criminal activity patterns.
