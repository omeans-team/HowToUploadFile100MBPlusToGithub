# How To Upload File 100 MB Plus To Github

- Download git lfs : [Download](https://github.com/git-lfs/git-lfs/releases/download/v3.4.1/git-lfs-windows-v3.4.1.exe)

- Initialize lfs on path your project : `git lfs install`
- select the file types you'd like Git LFS to manage (or directly edit your .gitattributes), example : `git lfs track "*.psd"`

## CLI/Github Desktop
- add, commit, push
![image](https://github.com/omeans-team/HowToUploadFile100MBPlusToGithub/assets/47584746/25ed10b8-8336-4aaa-af5a-ebffdcd09747)

## Bash/CMD
- `git add .gitattributes`
- `git add file.psd`
- `git commit -m "Summary name"`
- `git push origin main`
## Documentation
[Git LFS Documentation](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage)
