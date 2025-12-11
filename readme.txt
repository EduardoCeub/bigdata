1 - Docker Desktop aberto
2 - passar a pasta para o professor
3 - abrir o powershell dentro da pasta do trabalho. codigo: cd caminho da pasta
4 - docker build -t meu_trabalho_bigdata-notebook depois docker run -it --rm -p 8888:8888 -v "${PWD}:/home/jovyan/work" meu_trabalho_bigdata-notebook
5 - vai gerar o token no powershell, abrir o link http://127.0.0.1:8888/ no navegador.
6 - colar o token e abrir o trabalho