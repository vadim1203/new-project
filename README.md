README for new-project
1. mkdir new-project
2. cd new-project
3. git init
4. nano README.md
5. git add README.md
6. git commit -m "init"
7. git checkout -b development
8. nano README.md
9. git add README.md
10. git commit -m "Added instructions to README.md"
11. git checkout main
12. git merge development
13. git status
14. git remote add origin https://github.com/vadim1203/new-project.git
15. git branch -M main
16. git push -u origin main
17. git push -u origin development
