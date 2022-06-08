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

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

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

5. Вмержить ветку Bag Reports в Main

        $ git checkout main
        $ git merge Bug_Reports -m "merge Bug_Reports"

6. Запушить main на внешний репозиторий.

        $ git push

7. В ветке CheckLists набросать структуру чек листа.

        

8. Запушить структуру на внешний репозиторий

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

10. Синхронизировать Внешнюю и Локальную ветки Main
