# Set up for GPU servers

## Paperspace


### Persistent storage

How to use the papaerspace persistent storage to automatically recreate required environment.

For example, you can use pip install to install/upgrade packages in persistent storage

pip install -U --user packagename

here --user means that the package will be installed under .local directory

Then move to persistent storage

mv .local /storage/

create symbolic link between .local in storage and in home directory
ln -s /storage/.local 

You can also add ssh keys, or run anyother commands with the following.

If such a file exists, Paperspace will run the following before launching notebooks
/storage/pre-run.sh 

This file will be run when running a terminal
.bash.local


