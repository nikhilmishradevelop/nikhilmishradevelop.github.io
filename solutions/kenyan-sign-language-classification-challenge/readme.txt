A. A brief summary of the approach is in the file "approach.txt"

B. Instructions to reproduce the final solution:

1. Place the data in data folder

data/Train.csv
data/Test.csv
data/SampleSubmission.csv
data/Images

2. An output folder called 'outputs' is already created, all the model outputs will go to this folder. All the csv outputs are already saved in outputs folder as a reference.


3. On each notebook the top cell with command "!nvidia-smi" denotes which GPU the notebook was run on. Running notebooks on lower configuration GPUs may cause the code to fail, due to out of memory issues on CUDA. All the notebooks were run on `Google Colab Pro Plus`, so notebooks GPU vary, due to availability of GPUs at that time.

4. Run the following notebooks.

4.1 zindi_sign_conv_v5.ipynb
4.2 zindi_sign_conv_v7.ipynb
4.3 zindi_sign_effnet_v1.ipynb
4.4 zindi_sign_swin_v7.ipynb
4.5 zindi_sign_swin_v10.ipynb
4.6 zindi_sign_swin_v11.ipynb

4. Run the final notebook called zindi_blending.ipynb to produce the final solution

5. The final solution is called "blnd.csv". There might be little variations in the solution due to gpu reproducibility issues.


Finally thank you Zindi for organizing another wonderful competition. Looking forward to organizing more such competitions in the future.
