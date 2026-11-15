We have provided two methods to run the final solution:

A. On google colab
B. On your local machine


===================================================================================================================================================
A. Google Colab: Steps to get the final solution are described below.

1. Upload the notebook sub_final_v1.ipynb to google colab
2. Upload requirements.txt in the colab session.
3. Uncomment "pip install -r requirements.txt" in the first cell and then run the cell
4. Restart the notebook so the installed packages can be identified
5. Create a folder "data" and upload all competition files to this folder
6. Create another folder "outputs". This folder will contain the output submission file
7. Comment the first cell containing "pip install -r requirements.txt" 
8. Run the entire notebook sub_final_v1.ipynb
9. The output is stored in ./outputs/final_sub_v1.csv after the notebook has completed running


===================================================================================================================================================

B. Local Run: Steps to get the final solution are described below:

1. Create a new environment in conda with the dependencies

conda create --name comp python=3.7
conda activate comp
pip install -r requirements.txt

2. Create a folder "data" and add all competition files to this folder
3. Create another folder "outputs". This folder will the contain output submission file
4. Run the notebook (sub_final_v1.ipynb) from the environment
5. The final output is stored in ./outputs/final_sub_v1.csv after the notebook has completed running

===================================================================================================================================================
Thank you Zindi for organizing another wonderful competition. Please reach out to us for any clarifications.