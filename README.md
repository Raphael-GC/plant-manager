<h1 align="center">   
  Plant Manager
</h1>

<h2 align="center">   

  ![](https://github.com/Raphael-GC/plant-manager/blob/main/assets/favicon.png)  
</h2>

<h4 align="center">Atividade da Rocketseat NLW5, trilha React Native, voltada ao controle de regas no cultivo de plantas</h4>

<p align="center">
  <a href="# 🚀 Como ">Como executar</a> •
  <a href="# 💬 Funcionalidades">Funcionalidades</a> •
  <a href="# ⌚ Cronograma">Cronograma</a>
</p>

![](https://github.com/Raphael-GC/plant-manager/blob/main/assets/preview.png)

**Link figma:** https://www.figma.com/file/IhQRtrOZdu3TrvkPYREzOy/PlantManager/duplicate?node-id=0%3A1

## 🚀 Como executar
<ul>
  <li> 1. Primeiro, você precisa ter o Yarn instalado, então, para clonar o projeto via HTTPS utilize: </li>

`git clone https://github.com/Raphael-GC/plant-manager`

  <li> 2. Se você já possuir uma chave SSH cadastrada, clone utilizando: </li>

`git clone git@github.com:Raphael-GC/plant-manager.git`

  <li> 3. Depois de clonar, acesse a pasta do nosso projeto utilizando: </li>

`cd plant-manager`

  <li> 4. Dentro do repositório, baixe as dependências do projeto. </li>

  <li> 5. Para visualizar a aplicação em sua máquina utilize: </li>

  <ol> Windows - (Necessita de instalacao previa do Android Studio) </ol>

`yarn android` | `expo start`
  
  <ol> MacOS -  </ol>

`yarn ios` | `expo start`
</ul>

## 💬 Funcionalidades
<ul>
  <li>Listagem de plantas</li>
  <li>Adição e remoção de planta monitorada</li>
  <li>Definição de alarmes para lembretes</li>
  <li>Recebimento de alertas</li>
</ul>

## ⌚ Cronograma
<a>Dia 1</a> 
- Instalação de dependências (nodejs, react-native, expo-cli, typescript).
- Criação e estilização do componente Button.
- Explicação sobre Propriedades (Props) e Estados (useState).

<a>Dia 2</a>
- Refatoração do código feito ontem.
- Instalação da API do Expo voltada ao uso de ícones.
 
`expo install @expo/vector-icons`

- Instalação da API do Expo voltada ao uso de fonts (Usando o CDN do próprio Google Fonts).

`expo install expo-font @expo-google-fonts/inter`

- Instalação da API do Expo que utilizamos na tela de carregamento.

`expo install expo-app-loading`

- Instalação das APIs do React que utilizamos para navegação entre as páginas.

`yarn add @react-navegation/native`
`expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view`
`yarn add @react-navigation/stack`

- Criação das rotas e boas práticas de UX.

<a>Dia 3</a>
- Criação da página de seleção das plantas.
- Instalação de uma biblioteca do React Native que ajuda a fugir do notch do Iphone X.

`yarn add react-native-iphone-x-helper`

## :pencil: Author

- <a href="https://www.linkedin.com/in/raphael-gc/" target="_blank">LinkedIn</a>