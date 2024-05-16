Create a new repository on the command line

echo "# dotfiles" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:wilebaldosh/dotfiles.git
git push -u origin main
