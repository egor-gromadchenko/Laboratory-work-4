# Laboratory Work #4

## Перевірка версій програмного забезпечення з використанням GitHub Actions

У репозиторії створено GitHub Actions workflow `PrintSoftwareVersions.yml`, який містить дві роботи:

1. `print-data-processing-software-versions` — виводить версії програмного забезпечення рівня обробки даних:
   - Linux;
   - Node.js;
   - npm.

2. `print-database-software-versions` — виводить версії СКБД рівня доступу до даних:
   - MongoDB Server;
   - MongoDB Shell.

Workflow-файл розташовано у каталозі:

`.github/workflows/PrintSoftwareVersions.yml`
