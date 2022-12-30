# DevOps-1011-Tsyutsyak-HW05

Завдання

    Створити CI пайплайн для terraform-gitlab-module:
        тестування
            tfsec
            tflint
            checkov
        білд(збереження та публікація артефакта на Gitlab)
    Створити CI/CD пайплайн для dotnet app:
        білд
        тестування
        деплой інфраструктури*
        деплоймент аплікейшина*
    Перед білд стейджем додати кроки:
        linters (C#: dotnet-format або sonarlint, або інший відповідно до вашої мови програмування)
        code analysis (sonarqube)

*Підпункти завдання з виконанням по бажанню

Виконання завдання оформити у вигляді Pull Request з .gitlab-ci.yml. Посилання на pull request розмістити у особовому кабінеті.
