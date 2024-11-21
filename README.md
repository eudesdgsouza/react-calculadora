# 🧮 Calculadora-React  

Este projeto é uma calculadora elegante e responsiva, desenvolvida com **React**, que conta com funções matemáticas avançadas e animações suaves.  

## 🚀 Funcionalidades  

- Operações aritméticas básicas: soma, subtração, multiplicação e divisão.  
- Funções avançadas: seno, cosseno, tangente, logaritmo, raiz quadrada, exponencial, ln, arco seno, arco cosseno, arco tangente, valor absoluto.  
- Design responsivo, adaptado para diferentes tamanhos de tela.  
- Efeitos de estilo e animações atrativas.  
- Tratamento de erros para expressões inválidas.  

## 🛠 Tecnologias Utilizadas  

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.  
- **Styled-Components**: Para estilizar os componentes com CSS-in-JS.  
- **Math.js**: Biblioteca para realizar operações e avaliações matemáticas.  
- **React-Spring**: Biblioteca para adicionar animações aos componentes React.  

## 🛠 Configuração do Projeto  

Este projeto foi criado usando o [Create React App](https://github.com/facebook/create-react-app).  

### 📖 Scripts Disponíveis  

No diretório do projeto, você pode executar os seguintes comandos:  

#### `npm start`  
Executa o aplicativo no modo de desenvolvimento.  
Abra [http://localhost:3000](http://localhost:3000) no navegador para visualizar.  
A página será recarregada quando houver alterações. Também é possível visualizar erros no console.  

#### `npm test`  
Inicia o runner de testes no modo interativo.  
Veja mais sobre [execução de testes](https://facebook.github.io/create-react-app/docs/running-tests).  

#### `npm run build`  
Compila o aplicativo para produção na pasta `build`.  
O React é empacotado no modo de produção e a compilação é otimizada para o melhor desempenho.  
Os arquivos gerados estão minificados e prontos para serem implantados.  
Veja mais sobre [implantação](https://facebook.github.io/create-react-app/docs/deployment).  

#### `npm run eject`  
**Atenção: esta é uma operação irreversível.**  
Se você não estiver satisfeito com as ferramentas de compilação, pode usar este comando para copiar todos os arquivos de configuração para o projeto.  

## ⚙️ Como Funciona  

### Componentes React  

O projeto possui dois componentes principais:  

1. **Componente App**: O componente raiz, que aplica estilos globais e renderiza o componente `Calculator`.  
2. **Componente Calculator**: Contém a lógica para manipulação de entrada, execução de cálculos e exibição dos resultados.  

### Styled-Components  

Os estilos são aplicados diretamente nos arquivos dos componentes utilizando o Styled-Components. Isso garante uma separação clara entre lógica e estilo.  

Alguns dos principais styled-components incluem:  
- `GlobalStyle`: Estilos globais para toda a aplicação.  
- `Container`: Centraliza a calculadora na tela.  
- `CalculatorWrapper`: Estiliza o contêiner principal da calculadora.  
- `Display`: Estiliza a área de exibição de entrada e resultado.  
- `ButtonGrid`: Organiza os botões em formato de grade.  
- `Button`: Estiliza os botões com efeitos de hover e clique.  

### Math.js  

A biblioteca `math.js` é utilizada para avaliar as expressões matemáticas digitadas na calculadora, oferecendo uma ampla gama de funções para cálculos precisos.  

### React-Spring  

O `react-spring` adiciona animações suaves aos componentes, melhorando a experiência do usuário.  

### Tratamento de Erros  

Expressões matemáticas inválidas exibem uma mensagem de "Erro" no display.  
