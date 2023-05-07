README for new-project
1. mkdir new-project
2. cd new-project
3. git init
4. git remote add origin https://github.com/vadim1203/new-project.git
5. nano README.md
6. git add README.md
7. git commit -m "init"
8. git push -u origin main 
9. git checkout -b development
10. nano README.md
11. git add README.md
12. git commit -m "Added instructions to README.md"
13. git checkout main
14. git merge development
15. git status
16. git push -u origin main
17. git push -u origin development
