# LandfillDataset
1. Multispectral.7z : High resolution multispectral satellite image for landfill dataset along with annotations
2. Pansharpened.7z : High resolution pan sharpened satellite image for landfill datset along with annotations

#Uploading large dataset to github using Git Large File Storage

1. git lfs install
2. git lfs track "*.7z" 
3. git add .gitattributes
4. Next follow the standard git add, commit and push workflow ie:\
a. git add .\
b. git commit -m "Add your message"\
c. git push\

#Cloning an LFS on Google Colab
1. !apt-get update && apt-get upgrade\
2. !apt-get install git-lfs\
3. !git lfs clone https://github.com/AnupamaRajkumar/LandfillDataset.git

