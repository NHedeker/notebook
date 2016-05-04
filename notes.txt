#moves or renames files/directories
mv

#renames thing1 to thing2
mv thing1.txt thing2.txt

#moves thing1 to directory week1
mv thing1.txt /week1

#moves thing1 to week1 and renames it thing2
mv thing1.txt /week1/thing2.txt

#shortcut for ls -hl
ll

echo hi
grep "brew install" notes.txt
grep brew notes.txt
history
cat notes.txt | grep world
echo "hello world" > notes.txt
cat notes.txt
echo "hello n" >notes.txt

#creates notes.txt file
touch notes.txt

#lists all files and directories in working directory
ls

rm -r notebook

#changes to parent directory
..

#removes copyNotes.txt file
rm copyNotes.txt

cat copyNotes.txt notes.txt
cat copyNotes.txt
cp notes.txt copyNotes.txt

#opens notes.txt in atom
atom notes.txt

open notes.txt

#prints current working directory
pwd

#changes to directory Notebook
cd Notebook

#makes directory notebook within working directory
mkdir notebook

#lists info on rm command
man rm

cd Week1/
mkdir Week1
cd Projects/
cd Documents/

#shows tree view of files and directories
tree

#changes to the home directory
cd ~

cd ../
cd Library/Application\ Support/Google/Chrome/PepperFlash/

#changes to root directory
cd /

#shows info on the tree command
man tree

#shows directories and files in a level 2 tree
tree -L 2

#shows directories and files in a level 1 tree
tree -L 1

#installs tree via brew
brew install tree

echo
open ./Applications/

#opens home directory in finder application
open ~

#opens directory or files in finder application
open

#displays current username and its id number
id

ls -lt
ls -lS
man ls
ls -n
ls -lm
ls -li
ls -fl
ls -Fl
ls -lc
ls -halc
man l
ll ..
cat .config/fish/config.fish
ll .config/fish
ll .config
ls .config
ls -hal
ls -ahl
ls -lh
ls -hl
ls -l Documents/
ls Documents/ -l
ls Documents/
ls Do
ls -l
.
groups

#outputs current user
whoami

open http://nhedeker.surge.sh
surge
git commit -m 'Add a CNAME'
git add CNAME
touch CNAME
git commit -m 'Add a tiny webpage'
git add index.html
open index.html
atom .
touch index.html
git init
cd nhedeker.surge.sh
mkdir nhedeker.surge.sh
cd Projects
cd Documents
cd D
mkdir ~/Documents/Projects
surge -V
npm install -g surge
rm ~/Desktop/test.js
node ~/Desktop/test.js
atom ~/Desktop/test.js
node
node -v
brew install node
curl -fsSL https://git.io/vgqFH | sh
git config --global user.email
git config --global user.name
git config --global user.email 'Natasha.Hedeker@gmail.com'
git config --global user.name 'Natasha Hedeker'
which git
brew cleanup
brew outdated
git --version
which brew
echo $PATH
which which
which echo
/bin/echo
brew install git
echo $EDITOR
atom ~/.config/fish/config.fish
clear
ls -G
brew info fish
fish_update_completions
curl -fsSL https://git.io/vgqFU | ruby
chsh -s /usr/local/bin/fish
echo '/usr/local/bin/fish' | sudo tee -a /etc/shells
brew install fish
brew doctor
brew update
brew help
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
cd Documents -G
cd Applications
cd Precourse
cd Downloads
uname
