Sonarqube
=========

[![Travis-CI](https://travis-ci.org/deadc/deadcow.sonarqube.svg?branch=master)](https://travis-ci.org/deadc/deadcow.sonarqube)

SonarQube é uma plataforma de código fonte aberto para a análise da qualidade do código.

Requerimentos
------------
Nenhum

Variaveis
--------------

    sonarqube_version: 5.6.6
    
Define a versao a ser instalada do SonarQube

Dependencias
------------

Nenhum

Playbook exemplo
----------------

    - hosts: all
      roles:
         - { role: sonarqube }

Licença
-------

BSD

Author Information
------------------

Esta role foi desenvolvida por Thiago Freitas (deadcow@archlinux.com.br) em 03/2018
