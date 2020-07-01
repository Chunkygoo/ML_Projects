# ML_Projects
1. Clone repo: git clone https://github.com/CalvinTai0402/ML_Projects.git
2. Create a virtual environment: # py -m venv env # .\env\Scripts\activate OR # py -m venv envCPU # .\envCPU\Scripts\activate
3. Install dependencies: pip install -r requirementsGPU.txt (for GPU) or pip install -r requirementsCPU.txt (for CPU)


* How to upload big files to github: https://medium.com/@AyunasCode/how-to-push-large-files-to-github-253d05cc6a09, 
  https://towardsdatascience.com/uploading-large-files-to-github-dbef518fa1a. Essentially, download git lfs. Then 
  add the files to be tracked. Then run git lfs track "*.h5" (or whatever extension). You should see something like 
  'Tracking "*.h5"'. Then, add, commit like usual. Finally, run git lfs push --all origin master AND git push origin master.