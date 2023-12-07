Utilize o React e o Framer Motion e construa uma playlist em que você poderá mudar a ordem das músicas utilizando *drag and drop*! O objetivo desse mini projeto é tanto *descobrir como o Framer Motion facilita o uso de drag and drop* bem como entender como funciona, por trás dos panos, a lógica de reordenação de uma lista *drag and drop*.

## 🔨 Requisitos

- A aplicação deverá ser mobile-first. Construa pensando em um celular, e não em um monitor. 
- Utilize as biliotecas React + Framer Motion. 
- Crie o comportamento de "*drag and drop*":
	- Quando o usuário realizar um clique longo (sem soltar o mouse), o card de música devera "descolar" da aplicação e ser reordenável. 
	- Quando o usuário "soltar" o clique, a música deverá permanecer em sua nova posição. 
- Utilize o componente `Reorder` do Framer Motion.
- Estilize sua aplicação para ficar parecida com o design sugerido.

### Setup do Projeto

Você poderá fazer esse Mini Projeto de duas maneiras. A *primeira* é criando todo o setup do zero; a *segunda* é já utilizando um template com o layout pronto. Se você quer também treinar outras *skills* front-end como design e CSS, faça o projeto "do zero". Caso queira focar apenas nas bibliotecas principais (*react* e *framer motion*), utilize nosso template.

#### Fazendo tudo "do zero"

- Faça o setup do projeto como quiser, mas, visando maior facilidade, recomendamos fazer o setup com o [vite](https://vitejs.dev/).
- Utilize o Framer Motion na versão 10.12.7 (e não em versões posteriores, a não ser que esse [bug](https://github.com/framer/motion/issues/2183) esteja resolvido).

#### Iniciando com um template

Se você quer já utilizar nosso [template pré-pronto](https://github.com/codante-io/mp-drag-and-drop-framer-motion/tree/template), basta você ir para a branch `template` através do comando: `git checkout template`

Mas atenção: para que você tenha acesso a essa branch, na hora do fork no *github* você deverá desmarcar a opção "copiar apenas a branch `main`".

### Deploy

- Faça o deploy e submeta sua implementação no Codante.

## 🔍 Dicas

- Estude sobre a biblioteca `framer/motion`, pois ela possui ferramentas poderosas de animação.
- Estude particularmente o componente `Reorder` da biblioteca `framer/motion` - [link](https://www.framer.com/motion/reorder/)
- Utilize o Devtools do seu navegador com alguma pré-definição de tela mobile. O Chrome, por exemplo, [possui essa funcionalidade](https://developer.chrome.com/docs/devtools/device-mode/). 

## 🎨 Design Sugerido

Temos uma sugestão de design no Figma. Entretanto, fique à vontade para usar sua criatividade e criar um design único.

### Screenshot

![Design Sugerido](https://codante.s3.sa-east-1.amazonaws.com/challenges/readme-images/drag-and-drop-com-react-e-framer-motion.png)

### Figma - [link do design](https://www.figma.com/community/file/1276174742583537209)

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="100%" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FVoZiv3MR9jXHPD3yRWwVfD%2F%255BMini-Projeto%255D-Drag-and-Drop-com-React-e-Framer-Motion-(Community)%3Ftype%3Ddesign%26node-id%3D1%253A3%26mode%3Ddesign%26t%3DzbBTCrdR1hpKottd-1" allowfullscreen></iframe>

## 👉🏽 Sobre esse mini-projeto

### Tecnologias sugeridas

- **React**
- **Vite**
- **Framer Motion**

### Pré-requisitos

- `HTML, CSS`
- `JavaScript, React`

## ❓ FAQ

### Posso utilizar outras ferramentas além do Framer Motion para criar este mini projeto?

Claro que sim, mas o que recomendamos aqui (e é o objetivo deste mini projeto) é que você se familiarize com a funcionalidade de reordenação da biblioteca `framer motion`.

### Como faço para ver a resolução oficial?

A resolução oficial sempre é disponibilizada no [site oficial do Codante](https://codante.io). Verifique na [nossa agenda](https://codante.io/agenda) se data da resolução deste mini projeto já está definida.
