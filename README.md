# counterfit
use the counterfit framework to test risk analysis on machine learning models
********* SWITCH TO THE UPLOAD BRANCH IN ORDER TO PULL THE CODE"

Prerequisuites:
Python 3.7 or higher
Git
JupyterLab

Step 1.
To use the counterfit framework you are going to have to clone the repository from the "upload" branch of this repo
use the 'git clone' command

Step 2.
After cloning the repo, you are going to open up the terminal/console/.

Step 3.
Change directories with 'cd counterfit'

Step 4.
Create an instance of counterfit using 'conda create --yes -n counterfit python=3.8.8'

Step 5.
Use the activate command 'conda activate counterfit'

Step 6.
Install any missing requirements 'pip install -r requirements.txt'

Step 7.
Start counterfit 'python counterfit.py'

After starting counterfit run the following commands

1. To see the targets in the environment?
  ```
  list targets
  ```


2. Interact with a target
  ```
  interact satelliteimages
  ```


3. What's this model about?
  ```
  show info
  ```


4. What frameworks are there?
  ```
  list frameworks
  ```


5. Load the ART framework
  ```
  load art
  ```


6. List attacks
  ```
  list attacks
  ```


7. Use `hop_skip_jump`
  ```
  use hop_skip_jump
  ```


8. Show more information about the attack
  ```
  show info
  ```


9. Set parameters for the attack
  ```
  set init_size=50 max_iter=20 max_eval=500
  ```


10. What does the model think about the image at `sample_index=0` now?
  ```
  predict
  ```


11. Execute the attack
  ```
  run

12. Save to JSON

 save
