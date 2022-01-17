# Note-App
# Step 0. below should be executed in your local anaconda prompt window
# Step 1. initiate a new environment called note_app to avoid messing up with package versions in your base env
conda create --name note_app python=3.7
# Step 2. activate the env
conda activate note_app
# Step 3. go to the designated directory
cd "...\Note App" 
# Step 4. install dependencies
pip install -r requirements.txt --user
# Step 5. run the app 
python.exe "...\Note App\main.py"
