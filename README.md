# gif_tool

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/willianfrancisco/Conversor_Moedas/blob/main/LICENSE)

Aplicativo para compartilha Gifs.

# Sobre o Projeto
O Gif_Tool foi um projeto realizado durante estudos de desenvolvimento consumindo uma  API do site GIPHY Developers
- Mostra os Gifs que estão sendo exibidos no site.
- Pesquisar o gif desejado pelo nome na aba de pesquisa.
- Compartilhar os gifs. (clicando e segurando ou abrindo o gif e selecionando mais opçoes)

## Layout
![Mobile 1](https://github.com/willianfrancisco/Gif_tool/blob/master/Pagina_Inicial.PNG) 
![Mobile 2](https://github.com/willianfrancisco/Gif_tool/blob/master/Pagina_Pesquisa.PNG)
![Mobile 3](https://github.com/willianfrancisco/Gif_tool/blob/master/Pagina_Compartilhamento.PNG)

## Tecnologia Ultilizada
- Flutter 
- Dart
- Visual Studio Code
- Android Studio

## Bibliotecas Ultilizadas
- package:gif_tool/ui/gif_page.dart
- package:http/http.dart
- dart:convert
- share.dart

## Como Executar o projeto

```bash
# clonar o repositorio
https://github.com/willianfrancisco/Gif_tool.git

# usar o visual studio code ou android studio e abrir a pasta do projeto.
```

### Pré Requisitos
- Ter um Emulador Android Instalado.
- Ter o fluter Instalado e Configurado.
- Ter um editor como Android Studio ou Visual Studio Code(Com extensão do Fluter Instalado).

### Importante
- Algumas versões mais recentes do Flutter não vem com alguns puglins incluídos por padrão.
- Para incluir Devemos adicionar o plugin  no arquivo pubspec.yaml, o projeto ultiliza os seguintes plugins.
  - cupertino_icons: ^1.0.2
  - share: ^0.6.1+1
  - transparent_image: ^1.0.0
  - http: ^0.12.0+2
- Tome bastante cuidado com o alinhamento! O plugin deve ficar no mesmo alinhamento do cupertino_icons e logo abaixo do mesmo!
- Logo após clique no botão flutter packages get, caso não apareça a opção o seu flutter já possui o pacote Http instalado.

## Autor
Willian Francisco de Souza

https://www.linkedin.com/in/willian-francisco-b47605127/
