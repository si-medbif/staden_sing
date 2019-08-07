# Singularity image for Staden Package

****Definition file still does not work properly****
## How to build
Copy the definition file (staden.def) to the target directory.
Run the following command (rename <image_name> to the name you want e.g. staden.sif)
```
$ sudo singularity build <image_name>.sif staden.def
```

## How to access the image
Run the following command to access image (shell)
```
$ singularity shell <image_name>.sif
```
