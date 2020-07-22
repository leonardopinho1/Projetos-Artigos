## Projeto Arquitetura de Dados

Arquitetura de dados com o foco de atender um cliente que possui uma loja física e um e-commerce na nuvem (IAAS). Como o objetivo é investir no e-commerce trabalhamos com o Apache Flume para a coleta de dados com o objetivo de aproveitar seu poder de processamento, efetuamos o armazenamento dos dados em um Data Lake, em seguida enviamos para um "R" para análises, e para finalizar podemos consumir esses dados utilizando o Tableau que via dashboard e app disponibilizarão esses dados para consumo (Real Time).

No cenário de loja física podemos ter um ambiente mais enxuto, onde a idéia seria ter um ETL para coletar os dados, armazenar em uma base SQL tendo em vista que teremos somente dados estruturados, a partir disso podemos utilizar o Amazon Redshit para BI e analytics e para finalizar utilizaremos o o Tableau para disponibilizar as informações (No Real Time)

![alt text](https://github.com/leonardopinho1/Projetos-Artigos/blob/master/0.jpg)

