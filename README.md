# Usage
## Installing Git LFS
[Git LFS](https://git-lfs.github.com/) is used to host the large csv files. You need install and initialize Git LFS before cloning the repository. 
1. Install Git LFS by running
```bash
sudo apt install git-lfs
```
2. Initialize Git LFS by running
```bash
git lfs install
```
Don't worry if you see the following message which is completely harmless.
> Error: Failed to call git rev-parse --git-dir --show-toplevel: "fatal: not a git repository (or any of the parent directories): .git\n"<br/>
Git LFS initialized.


## Cloning the Repository
To clone the repository to your local hard drive, run
```bash
git clone https://github.com/ral-stevens/CPE521Final.git
```
Messages as follows will be printed out in the terminal:
> Cloning into 'CPE521Final'...<br/>
remote: Enumerating objects: 9, done.<br/>
remote: Counting objects: 100% (9/9), done.<br/>
remote: Compressing objects: 100% (9/9), done.<br/>
remote: Total 9 (delta 0), reused 9 (delta 0), pack-reused 0<br/>
Unpacking objects: 100% (9/9), done.<br/>
**Filtering content: 100% (4/4), 376.51 MiB | 10.12 MiB/s, done.**<br/>

You will not see the last line "Filtering content..." shown above if Git LFS is not correctly installed.

## Executing the Python script
Navigate into the directory you just cloned by running:
```bash
cd CPE521Final
```
Then run
```bash
./convert_csv_to_bag.py
```

# Questions
Please email Zhuo Chen at zchen39@stevens.edu if you have any questions.
