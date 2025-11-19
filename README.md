FLASKQS

Creating this program was a bit of a challenge
but due to this project I really have a better understanding of virtual environments 

Step 1: Create a virutual environment.
For macOS/Linux: python3 -m venv venv
For Windows: python -m venv venv

Step 2: Activate the environment
For macOS/Linux: source venv/bin/activate or . venv/bin/activate
For Windows: venv\Scripts\activate

Step 3: Install Packages
pip install requests flask numpy
Check installed packages with: pip list

Step 4: Freeze / reproduce environment
pip freeze > requirements.txt

Step 5: Deactivate & Remove
For macOS/Linux: rm -rf venv
For Windows: rmdir /s venv
