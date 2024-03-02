# lesson23

**Домашнее задание**

взять стенд https://github.com/erlong15/vagrant-bind </br>
добавить еще один сервер client2</br>
завести в зоне dns.lab</br>
имена</br>
web1 - смотрит на клиент1</br>
web2 смотрит на клиент2</br>
завести еще одну зону newdns.lab</br>
завести в ней запись</br>
www - смотрит на обоих клиентов</br>
настроить split-dns</br>
клиент1 - видит обе зоны, но в зоне dns.lab только web1</br>
клиент2 видит только dns.lab</br>

Скачал стенд, внес изменения согласно описанию в методичке, протестировал доступность по сети

Подключение к client

![image](https://github.com/movik242/lesson23/assets/143793993/33212a54-57a3-4dd8-83e2-05c6d172de36)

Тест с клиента

![image](https://github.com/movik242/lesson23/assets/143793993/faa2e1b5-17a6-4496-a26a-0b2f9e440c0e)

Тест с клиента2

![image](https://github.com/movik242/lesson23/assets/143793993/01c1b90e-2c12-4b1b-be56-5d6e6025f797)

