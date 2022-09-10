# Projeto BookletNFT
## Projeto Final de Curso - LEIM 2021/2022
### Alunos:
#### Miguel Silvestre 45101
#### Pedro Henriques 45415
### Orientadores:
#### Hélder Bastos
#### Paulo Trigo

### Como executar
1 - [Instalar docker](https://docs.docker.com/get-docker/)

2 - Fazer pull da imagem `docker pull miguelsilvestre1999/projeto_final:latest`

3 - Correr a partir de docker desktop ou a partir da linha de comandos `docker run -dp <porta-no-pc>:<porta-docker> miguelsilvestre1999/projeto_final`

4 - Aceder ao localhost 3000

### Organização das pastas
- A pasta 00_Planeamento contém um ficheiro excel com a agenda de planeamento do projeto.
- A pasta 01_Analise contém os casos de utilização desenvolvidos e os requisitos do sistema.
- A pasta 02_Desenho contém imagens utilizdas no desenvolvimento do projeto
- A pasta 03_Implementação contém o código desenvolvido
- A pasta 04_Teste contém um txt chamado _nao_aplicavel

### WARNING
A primeira vez que se fizer build da imagem do docker irá consumir bastante memória e a máquina poderá ficar lenta. Não se recomenda a utilização para quem esteja a usar uma máquina menos potente. Em situações normais a primeira execução pode demorar até 20 minutos.
