# Задание №1<br>

- Опишите своими словами основные преимущества применения на практике IaaC паттернов.<br>
- Какой из принципов IaaC является основополагающим?<br>

## Ответ

1. IaaC является увеличение степени автоматизации развёртывания инфраструктуры, а соответственно увеличение скорости выполнения 
этой операции и снижение трудозатрат на её выполнение.<br>

2. Принципом IaaC является обеспечение создания/настройки инфраструктуры аналогично процессу разработки программного обеспечения.<br>
_________________

# Задание №2

- Чем Ansible выгодно отличается от других систем управление конфигурациями?<br>
- Какой, на ваш взгляд, метод работы систем конфигурации более надёжный push или pull?<br>

## Ответ

1. Главное его отличие от других подобных систем в том, что Ansible использует существующую SSH инфраструктуру, 
в то время как другие (Saltstack, Chef, Puppet, и пр.) требуют установки специального PKI-окружения.<br>

2. Pull, т.к. отсутствует единая точка отказа и хранения данных для доступа.<br>
____________________
# Задание №3

Установить на личный компьютер:<br>

- VirtualBox<br>
- Vagrant<br>
- Ansible<br>

Приложить вывод команд установленных версий каждой из программ, оформленный в markdown.<br>

## Ответ

```
pi@pi:~$ vboxmanage -v
6.1.32_Ubuntur149290
```
```
pi@pi:~$ vagrant -v
Vagrant 2.2.19
```
```
pi@pi:~$ ansible --version
ansible 2.10.8
  config file = None
  configured module search path = ['/home/pi/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python3/dist-packages/ansible
  executable location = /usr/bin/ansible
  python version = 3.10.4 (main, Apr  2 2022, 09:04:19) [GCC 11.2.0]
```
______________

  
