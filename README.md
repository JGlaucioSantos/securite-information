# Sécurité de l'information

#### 1 passo - criar um diretorio projeto-glaucio 

```bash
mkdir -p projeto-glaucio
```

2 passo - acessar a pasta $ cd projeto-glaucio

3 passo - abrir o visual code $ code .

4 passo - criar a configuracao do ambiente (venv = gerenciador de ambiente $ python3 -m venv .venv
obs: arquivo ou pasta comecando com ponto, fica oculto no diretorio

5 passo - ativar o ambiente $ source .venv/bin/activate

6 passo - criar o aquivo da apliacao $ touch app.py

7 passo - permissao de execucao $ chmod +x app.py

8 passo - capturar o interpretador $  which python3
  copiar e colocar no capecario do aplicativo comecando por #!

9 passo - Atualizacao do ambiente virtual $ pip install -U pip setuptools wheel
  -U significa que ele vai fazer a atualizacao das tres bibliotecas pip,setuptools e  wheel
commande $ pip freeze - mostra quais sao as bibliotecas e as respectivas versoes
commande $ pip list - lista as bibliotecas existente 

10 passo - Instalar as bibliotecas requests que serve para fazer as requisicoes $ pip install requests 

11 passo - Criar o arquivo de requiments.txt serve para mostrar a biblioteca e a versao sendo utilizada $ pip freeze > requiments.txt

12 passo - Para atualiza o arquivo requiments.txt $ pip install -r (recursivo) requiments.txt

13 passo - Intalando a biblioteca "pandas" que serve para manipular base de dados como: datasets, lista, cria tabelas etc.$ pip isntall pandas