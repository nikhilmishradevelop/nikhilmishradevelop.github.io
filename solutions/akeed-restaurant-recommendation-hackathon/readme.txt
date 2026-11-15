Configuration :
-------------

The notebooks were run on Kaggle with  16GB RAM, on two separate kernels, so for it to run smoothly on a single machine, please use atleast 24 GB of RAM.

Input Files :
-----------

All the competition input data is present in 'input_data' directory.

Final Output File/Submission File :
---------------------------------

'zindi_weekend_food_recommendation_final_solution.csv' present in 'output_data' directory.

Steps:
-----

Run the notebooks in the following order (the second notebook depends on the output of the first notebook)

1. '1.akeed_weekend_preparing_data.ipynb' generates 'train.pkl' and 'test.pkl' as outputs in 'output_data' directory after processing the given input files.
  "These two files take up a good amount of space so make sure to have free hard-disk space."
2. '2.akeed_weekend_final_solution.ipynb' generates the final output using 'train.pkl' and 'test.pkl' submitted as 'zindi_weekend_food_recommendation_final_solution.csv'.


Libraries Used :
--------------

Scikit-learn, Numpy, Pandas and Light-GBM, along with Core-Python Libraries.

Remarks:
--------

1. Due to seeding issues, I am unable to generate the exact solution submitted.
2. The notebooks are completely commented to enable better understanding.

P.S: Thank you Zindi for successfully conducting another wonder Zindi Weekend hackathon. Looking forward to participate and help grow this wonderful Zindi community. Please do reach out to me in case of any queries.