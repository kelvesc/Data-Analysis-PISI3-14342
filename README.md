# PISI3 - BSI - UFRPE
por: Gabriel Alves (gabriel.alves@ufrpe.br)

Este projeto é utilizado para as aulas da disciplina de Projeto Interdisciplinar para Sistemas de Informação 3 (PISI3), do 3° período do curso de Bacharelado em Sistemas de Informação (BSI) da Sede, da Universidade Federal Rural de Pernambuco (UFRPE).

## Instalação:
<ol>
  <li>Instale o VSCode.</li>

  <li>Efetue o clone do projeto: <code>CTRL+SHIFT+P > Git:Clone > Clone from GitHub > https://github.com/gaaj-ufrpe/pisi3-bsi-ufrpe</code></li>

  <li>Instale o python.</li>
  
  <li>Acesse a aba "Terminal" disponível na parte inferior do VSCode.</li>

  <li>Execute a linha abaixo para criar um ambiente virtual do python para o projeto. Observe que a pasta <code>venv</code> está no <code>.gitignore</code>.<br>
    <code>python -m venv venv</code>
  </li>

  <li>Atualize o pip:<br>
    <code>python -m pip install --upgrade pip</code>
  </li>

  <li>Instale as libs necessárias para o projeto:<br>
    <code>pip install -r requirements.txt --upgrade</code>
  </li>

  <li>Rode o sistema:<br>
    <code>streamlit run Home.py</code>
  </li>
</ol>

## Informações Adicionais:

Este projeto tem 3 branches com códigos distintos:
<ol>
  <li>main: código com várias funcionalidades diferentes: sidebar, pandas, arquivos parquet, ydata-profile, clusterização etc.</li>
  <li>basics: código inicial com o uso básico do streamlit. Possui uma caixa de texto e exibe uma mensagem ao preenchê-la.</li>
  <li>theme: código para mostrar como funciona o uso de temas no streamlit.</li>
</ol>

Repositório: https://github.com/gaaj-ufrpe/pisi3-bsi-ufrpe<br>
Disponível em: https://gaaj-pisi3-bsi-ufrpe.streamlit.app/<br>
Classroom: <a href="https://classroom.google.com/c/NjExNTAzOTU4MDQy?cjc=7qgaz7u">https://classroom.google.com/c/NjExNTAzOTU4MDQy?cjc=7qgaz7u</a><br>
Acesse: <a href="bsi.ufrpe.br">bsi.ufrpe.br</a><br>
Contato: gabriel.alves [at] ufrpe.br<br>