This repository contains the implementation used for the experimental evaluation reported in the paper.

**1: Install the required dependencies:**  
pip install torch torchvision torchaudio  <br>
pip install torch-geometric  <br>
pip install numpy pandas scikit-learn tqdm transformers<br>

**2. Project Structure**<br>
.
├── config/        # Configuration files
├── data/          # Data preprocessing scripts
├── dataset/       # Dataset loader
├── graph/         # Graph construction modules
├── model/         # Model definitions
├── train/         # Training and evaluation scripts
├── utils/         # Utility functions
├── outputs/       # Saved models and logs
├── Tweets.xlsx    # Dataset file
└── main.ipynb     # Main execution notebook

**3. Dataset Preparation**<br>
Download Data Set (https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)<br>

**4. Running the Experiments**<br>
Open and run main.ipynb

**5. Outputs**<br>
Model evaluation results are saved in **outputs** folder:

