# CLICOM

This repository is an archive of sample CLICOM data.

Some files in this repository are greater than 100 Mb therefore
we have enabled [Large File Storage (LFS)](https://git-lfs.github.com/)
using the following commands:

```
sudo apt install git-lfs
git lfs install

# In the root of the repository
git lfs tract "*.dat"
git lfs tract "*.csv"
git add .gitattributes

```
