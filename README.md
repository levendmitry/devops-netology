Будут проигнорированы:

Локальная директория .terraform и вложенные в него файлы в любом месте репозитория

Файлы, содержащие в названии .tfstate. или заканчивающиеся на .tfstate

Файл логирования crash.log и любые файлы начинающиеся на crash.и при этом оканчивающиеся на .log

Файлы с расширением .tfvars .tfvars.json файлы содержащие важные данные такие как пароли, персональные ключи и прочее

Игнорируются файлы переопределения ресурсов, обычно они используются локально это файл override.tf, override.tf.json и фалы оканчивающиеся на override.tf и override.tf.json

Файлы CLI конфигурации .terraformrc и terraform.rc

anotherline
