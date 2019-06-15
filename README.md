## Домашка к уроку по Ansible

В репо содержится vagrant-file, который поднимает 2 виртуалки на разных ОС - Ubuntu и CentOS7 и 2 роли:
+ ##### deploy_nginx (Устанавлвивает nginx, делает кастомный конфиг и создает index.html на основе шаблонов)
+ ##### install_packages (устанавливает некоторое количество ПО)

Для каждой роли создана свой playbook, со следующими именами (названия говорят сами за себя):
+ #####nginx_deploy
+ #####install_packages

## Usage:

Необходим установленный vagrant и ansible на хостовой машине.
##### Vagrant up
поднимает наши виртуалки.

##### ansible-playbook  playbooks/name_of_playbook.yml
запускает плейбуку и соответсвующую ей роль.


