# Build web applications with ansible

### 0. 개요
- Ansible은 Devops도구로서 IT인프라를 쉽게 관리하기 위한 도구입니다.

  코드로서 인프라를 구축하기 때문에 infrastructure as code라고 불리기도 합니다. 

  시스템 구성시 다양한 애플리케이션을 환경에 맞게 설치하고 관리해야 하는데 ansible은 이러한 일련의 작업들을 자동화하는데 도움을 주는 도구입니다.

  강의에서는 ansible을 이용하여 nginx, mysql(mariadb), php, wordpress를 구축하는 실습을 진행합니다.

- daddyprogrammer.org에서 강의 연재를 하고 있으며 Github에 소스가 등록되어 있습니다.
  - Document
    - https://daddyprogrammer.org/post/series/learn-ansible/
  - Githup Repository
    - https://github.com/codej99/ansible-web-application

### 1. 실습 환경
- Ansible
- Vagrant
- VirtualBox
- Create a playbook using vscode
- Mac, Windows10

### 2. 가상환경 테스트 
- Vagrant로 VirtualBox에 VM 생성
    - $ cd virtual-env
    - $ vagrant up
    - $ vagrant provision
- ansible playbook 실행
    - $ cd virtual-env
    - $ vagrant ssh ansible-server
    - $ ansible-playbook 플레이북.yml
       
### 3. 목차
- Ansible을 이용한 시스템 구성관리(1) – Vagrant를 이용한 테스트 가상환경 만들기
    - https://daddyprogrammer.org/post/7369/ansible-vagrant/
- Ansible을 이용한 시스템 구성관리(2) – ansible로 nginx 설치 – roles, handler, template, vars
    - https://daddyprogrammer.org/post/7615/ansible-nginx-roles-handler-template-vars/
- Ansible을 이용한 시스템 구성관리(3) – ansible로 mysql(mariadb) 설치 자동화
    - https://daddyprogrammer.org/post/7840/ansible-mariadb/
- Ansible을 이용한 시스템 구성관리(4) – wordpress (nginx+mariadb+php) 설치 자동화
    - https://daddyprogrammer.org/post/8393/ansible-wordpress-nginx-mariadb-php/
