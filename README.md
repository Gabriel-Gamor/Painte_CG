# Construção do Paint ultilizando OpenGL e Glut para a cadeira de Computação Gráfica

Este projeto é um programa em C que permite a criação, manipulação e visualização de objetos geométricos, incluindo pontos, segmentos de reta e polígonos, utilizando a biblioteca OpenGL e GLUT para renderização gráfica.

OBS: Esse é um porte do projeto para Windows, o projeto original feito no Ubuntu 24.02 está no repositorio https://github.com/LucasAngel0/Paint_CG

## Funcionalidades
  - Criar Objetos: Permite criar pontos, segmentos de reta e polígonos na tela utilizando o mouse.
  - Selecionar Objetos: Seleciona objetos criados para manipulação.
  - Salvar e Carregar Objetos: Os objetos podem ser salvos em arquivos de texto 
   e carregados posteriormente.

## Manipulação de Objetos:
  - Escalar objetos (aumentar ou diminuir)
  - Rotacionar objetos
  - Deletar objetos
  - Finalizar a criação de polígonos
  - Refletir o Objeto em y e em relação a origem.
  - Cisalhar Poligono

- Criar e manipular pontos, segmentos de reta e polígonos.
- Salvar e carregar objetos de arquivos.
- Selecionar objetos com o mouse.
- Manipulação básica de objetos (exclusão, escalonamento e rotação) através do teclado.

## Instruções para Execução do Projeto

- Instalar em C:\MinGW (<MINGW_HOME>) -> Na instalação do MinGW, instalar os pacotes básicos “mingw32-base”, “mingw32-gcc-g++” e “msys-base” -> Colocar os diretórios <MINGW_HOME>\bin e <MINGW_HOME>\msys\1.0\bin na variável de ambiente Path do Windows -> Faça a Instalação das bibliotecas GLU e FreeGLUT (GLUT) no MinGW
- Execulte "../bin/Debug/Painte_CG-main.exe" Ou Importe o Projeto para o CodeBlocks e execulte

## Instrução Para Uso
### Menu de Contexto

  #### Acesse o menu principal clicando com o botão direito do mouse.
  - O menu permite criar, selecionar, salvar, carregar objetos e sair do programa.
  #### Interação com o Mouse
  - Clique com o botão esquerdo para adicionar ou selecionar objetos.
   Os objetos são criados ou selecionados dependendo da opção ativa no menu.

### Controles 
Com o objeto selecionado de acordo com o menu de contexto aperte as seguintes teclas(maiusculas ou minusculas)  para executar a funcionalidade requerida 
- F: Finaliza o desenho do polígono.
- D: Deleta o objeto selecionado.
- L: Aumenta o objeto selecionado.(exceto o Ponto)
- K: Diminui o objeto selecionado para baixo.
- R: Rotaciona o objeto selecionado em sentido horário.(o Ponto é rotacionado  ao redor da origem)
- E: Rotaciona o objeto selecionado em sentido anti-horário.(o Ponto é rotacionado  ao redor da origem)
- M: Reflete o objeto como base na origem
- N: Reflete o objeto com base o Eixo Y
- C: Cisalha o polígono em x
- V: Cisalha o polígono em Y
- A: Realiza uma animação com os objetos
  
  


