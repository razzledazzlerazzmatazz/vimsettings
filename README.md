# vimsettings

Install Vundle
--------------
Install Vundle from [here](https://github.com/VundleVim/Vundle.vim).

To set it up, all you have to do is:

```
# clean up vim ~/.vim folder
rm -rf ~/.vim
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
 ```

Make sure you have Exhuberant ctags installed:

```
sudo port install ctags
# or
apt-get install ctags
# or
yum install ctags
```

Set up Vim
----------
Copy the vimrc file to ~/.vimrc.

```
cp vimrc ~/.vimrc
```

Start vim and type 

```
:VundleInstall
```
