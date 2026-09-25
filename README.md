# ai-physics-Aguilar-Mayorga

#Contains:
*
README: explaining a general overview of the repository
*.gitignore : file listing the files to ignore by github when pushing my initial commit. It allows me to add the API KEY to an .env to use it in the .ipynb, but not uploading it to keep it private (it exists locally in my laptop, but not in the public repository)
* .environment.yml: file containing all the necesary details to replicate the used environment in case anyone else wants to use this repository. It makes it easier for that new user to replicate my environment by just adding the following commands in their terminal:
conda env create -f environment.yml
conda activate ai-physics
