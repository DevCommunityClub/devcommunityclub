…or create a new repository on the command line

echo "# devcommunityclub" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M Master
git remote add origin https://github.com/DevCommunityClub/devcommunityclub.git
git push -u origin Master
                

…or push an existing repository from the command line

git remote add origin https://github.com/DevCommunityClub/devcommunityclub.git
git branch -M Master
git push -u origin Master