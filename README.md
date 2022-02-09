# lfs-test

This repo can be used for testing git lfs support in Gitpod.

The file [.gitattributes](.gitattributes) is configured to track all `.png` files in LFS.  

```gitattributes
*.png filter=lfs diff=lfs merge=lfs -text
```

The file [screenshot.png](screenshot.png) is stored in LFS, not git.  

![Screenshot 2022-02-08 at 20 39 17](https://user-images.githubusercontent.com/849592/153072221-ef14cf3a-c395-4441-851f-a90575f741d3.png)