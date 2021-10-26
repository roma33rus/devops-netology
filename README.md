# devops-netology

Roman Piskarev


Для всех файлов gitignore корнем будет считаться папка terraform/
1. Игнорироваться будет папка .terraform и все файлы в ней в корневой дирректории и во всех подпапках любой вложенности.
2. Любые файлы с расширением tfstate и файлы с именем *.tfstate.*
3. Файл в корне crash.log
4. Файлы с расширением tfvars
5. Файлы с именами: override.tf и override.tf.json. А так же файлы, имена которых оканчиваются на _override.tf и _override.tf.json
6. Так же будут игнорироваться файлы с именами .terraformrc и terraform.rc