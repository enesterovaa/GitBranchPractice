# Programs

1. На локальном репозитории сделать ветки для:
>- Postman
>- Jmeter
>- CheckLists
>- Bug Reports
>- SQL
>- Charles
>- Mobile testing

        $ git branch Postman
        $ git branch Jmeter
        $ git branch CheckLists
        $ git branch Bug_Reports
        $ git branch SQL
        $ git branch Charles
        $ git branch Mobile_testing

2. Запушить все ветки на внешний репозиторий

        $ git push -u origin --all

3. В ветке BUg_Reports сделать текстовый документ со структурой баг репорта

        $ cat >> bug_report_structure.txt
        Summary
        Project
        Component
        Version
        Severity
        Priority
        Status
        Author
        Assigned to
        Description
        Steps to reproduce
        Expected result
        Actual result
        Attachment

4. Запушить структуру багрепорта на внешний репозиторий

        $ git add .
        $ git commit -m "add bug_report_structure"
        $ git push

5. Вмержить ветку BUg_Reports в Main

        $ git checkout main
        $ git merge Bug_Reports -m "merge Bug_Reports"

6. Запушить main на внешний репозиторий.

        $ git push

7. В ветке CheckLists набросать структуру чек листа.

        $ cat >> CheckList1.txt
        1) Build
        2) Environment
        3) Test date
        4) Tester
        5) Test type
        6) Checking
        7) Result

8. Запушить структуру на внешний репозиторий

        $ git add
        $ git commit -m "add CheckList1.txt"
        $ git push

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

        Pull requests -> Compare & pull request -> Create pull request - Merge pull request

10. Синхронизировать Внешнюю и Локальную ветки Main

        $ git pull
