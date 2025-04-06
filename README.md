

![bannerprincipal](https://github.com/user-attachments/assets/9c1be550-0d60-4682-86d8-d8e1901f0642)


# 🌸 Sobre o projeto
<p> Bem-vindos ao meu Portfólio de Transição de Carreira </p>
<p>Estou embarcando numa jornada épica para me tornar uma desenvolvedora, e este portfólio é o meu espaço para aprender e evoluir!</p>
<p>Aqui, vocês vão ver um pouco do meu dia a dia no mundo do JavaScript, TypeScript, e até um básico de React. Afinal, a transição de QA para Dev não é fácil, mas com cada linha de código, estou mais animada para explorar o universo da programação! Sim, eu sei que o caminho vai ser longo e cheio de desafios (e alguns bugs, claro! 😅), mas estou determinada a dar o meu melhor todos os dias.  E, como sempre, vamos focar nas coisas boas, porque quem não gosta de um commit bem-sucedido e uma interface maravilhosa? 🌸</p>
<p>Siga-me nessa jornada e acompanhe meu progresso – cada projeto é um passo para me tornar a dev dos meus sonho rosa. </p>

# 🌸 Fedbacks e Code Review
Se você está visitando este repositório, fico muito grato pelo seu tempo e atenção. Seu feedback ajuda no meu crescimento como desenvolvedora, então, por favor, sinta-se à vontade para comentar ou sugerir melhorias nos commits.
Se você está aqui, tenho orgulho de trabalhar com você e aprender juntas! 

# 🌸 Diário - Dia 03 de abril de 2025
♫ Indicação de musica: Gabriela (TECH LEAD - DEV FRONT) ♪ 

<img width="557" alt="image" src="https://github.com/user-attachments/assets/650462f5-8f30-494f-aeb3-e9c2f8fbc0df" />

★ ★ ★ Status do curso: Módulo 1: Iniciando com React ★ ★ ★ 

Observação: O curso já iniciou com o Git e o repositório prontos, então hoje aproveitei para criar um novo repositório pessoal, seguindo os passos abaixo:

```sh
Criar um repositório Git 

• Acessei meu GitHub pela página inicial: https://github.com/

• Ao lado do meu nome, cliquei no botão "New"

• Selecionei a opção "Create a new repository"

• Escolhi um nome e escrevi uma descrição para o repositório
```
• Hoje compartilhei o repositório com a equipe para que todos fiquem cientes e possam fornecer feedbacks construtivos.

♥ ♥ ♥ Agradecimentos ♥ ♥ ♥ 

Paulo (DEV FRONT), por me proporcionar o curso "Commit: Iniciando com React - Criando um projeto React", e por estar sempre se oferecendo para ajudar e dando ótimos conselhos sobre Front-end.

Gabriela (TECH LEAD - DEV FRONT), mesmo estando de férias, tem me apoiado durante essa nova transição de carreira.

Cláudio (COORDENADOR), Isabella (MANAGER QA) e Samanta (STAFF QA), por sempre me manterem confortável com essa nova etapa e estarem dispostos a me ajudar.


# 🌸 Diário - Dia 04 de abril de 2025
Dificuldade do dia: Achar qual era o fundo dentro do projeto, pois era cor branca.
Depois pesqueisei e achei o background.
Links: Cores do HTML https://www.homehost.com.br/blog/tutoriais/tabela-de-cores-html/

♫ Indicação de musica: Dennis (DEV BACK) ♪ 
 
![image](https://github.com/user-attachments/assets/937e2950-f6c2-4950-92cb-4a217cfc5f85)

Título: Instalação  Nodejs 

Descrição: Node.js é um ambiente de execução JavaScript gratuito, de código aberto e multiplataforma que permite aos desenvolvedores criar servidores, aplicativos da web, ferramentas de linha de comando e scripts.

```sh


• Link do site: https://nodejs.org/en

• Para ver qual versão estamos do node:
zeuser@GHQML47YRFX RosaEmCadaCommit % node -v
v22.14.0

```

Título: Instalação da ferramenta Vite de construção para a Web

Descrição: O Vite é uma ferramenta de construção de frontend extremamente rápida que impulsiona a próxima geração de aplicativos web.


```sh
• Executar os comandos do link: https://vite.dev/guide/

• Ececuto o comando npm create vite@latest
- Nome da pasta: rosaemcadacommit
- Select a framework: React
- Select a variant: TypeScript

• Apos isso executar os comandos:
 - cd rosaemcadacommit
 - npm install
 - npm run dev
Nesse comando ele mostra uma porta
http://localhost:5173/

• [Aqui apareceu um erro para mim] Entao tive que informar a porta que estava sendo executada:
- Ir na pasta vite.config.ts
- E inserir o número da porta correta
- O código em si vai ficar:
// https://vite.dev/config/
export default defineConfig({
  plugins: [react()],
  server:{
     port: 5173,
  }
})
- Apos isso execute o comando novamente npm run dev 
- Acesse a porta [http://localhost:5173/] e veja se funcionou.

```
♥ ♥ ♥ Agradecimentos ♥ ♥ ♥ 

Paulo (DEV FRONT): Sempre tirando minhas duvidas e me dando apoio.

Arthur (DEV BACK): Por me tirar uma duvida no codigo.

Samanta (STAFF QA): Obrigada pelos 1:1, pelo apoio, e por sempre esta me ajudando positivamente nesse novo processo.

Dennis (DEV BACK): Pelo carinho e pelas conversas sobre começo de carreira.


# 🌸 Diário - Dia 06 de abril de 2025
♫ Indicação de musica: PAULO (DEV FRONT) ♪ 

<img width="733" alt="image" src="https://github.com/user-attachments/assets/011baf6d-2db0-4a98-938e-c8ba8f313617" />

Hoje o site está assim:
```sh
• Porta ultilizada: http://localhost:5173/

```

<img width="1047" alt="image" src="https://github.com/user-attachments/assets/82bad303-5f6d-4b26-813d-14af0eb4947b" />

✿ Plano de Testes: Mudar o Fundo do Projeto

✿ Cenário de Teste:
[CT01] Alterar o fundo do projeto para uma nova cor, verificando se a mudança é refletida corretamente na interface do usuário.

✿ Pré-condições:
- O projeto deve estar corretamente configurado e rodando localmente ou em um servidor de desenvolvimento.
- O ambiente de desenvolvimento deve estar funcionando corretamente (ex.: editor de código, terminal, navegador).
- O sistema de controle de versão (ex.: Git) deve estar configurado e funcionando (para salvar as alterações).

✿ Passos para Execução:
- Abrir o código-fonte do projeto:
http://localhost:5173/
- Alterar o fundo do projeto
Ps: Para mudar a cor do fundo, localize a propriedade de fundo no CSS, e altere o valor para a cor desejada (ex.: background-color: #f0f0f0;).
- Salvar as alterações no arquivo de estilo.
- Verificar se o fundo foi alterado corretamente.
- Atualize a página no navegador.
- Observe se a alteração do fundo foi aplicada corretamente.

No código alterei o fundo:
Hoje o site está assim:
```sh
•   :root {
    color: #213547;
    background-color: #FF69B4;
  }

```

♥ ♥ ♥ Agradecimentos ♥ ♥ ♥ 

Samanta (STAFF QA): Obrigada pelas conversas, que mesmo nos finde semana sempre sao otimas e rende boas risadas.

# 🌸 Diário - Dia 06 de abril de 2025
♫ Indicação de musica: Grazi (DEV BACK) ♪ 

<img width="638" alt="image" src="https://github.com/user-attachments/assets/50c64b92-1790-4c78-a3dd-a89ab49184b0" />

✿ Plano de Testes: Colocar uma Imagem no Código
✿ Cenário de Teste:
Testar a exibição correta da imagem inserida no código React, verificando se a imagem é carregada corretamente e se os estilos aplicados (como tamanho e centralização) estão funcionando como esperado.

✿ Pré-condições:
O ambiente de desenvolvimento deve estar configurado corretamente (Vite + React).

A imagem a ser inserida deve estar no diretório correto dentro do projeto (por exemplo, src/assets/images/bannerprincipal.jpeg).

O servidor de desenvolvimento do Vite deve estar em execução.

✿ Passos para Execução:
Verificar se a imagem está no diretório correto:

Confirmar que a imagem (por exemplo, bannerprincipal.jpeg) está localizada na pasta src/assets/images/ do projeto.

Importar a imagem no arquivo JSX/TSX:

No arquivo onde a imagem será exibida (por exemplo, App.tsx), adicionar a importação da imagem:

tsx
Copiar
import bannerPrincipal from './assets/images/bannerprincipal.jpeg';
Adicionar a tag <img /> no JSX:

No componente React, adicionar a tag <img /> com a imagem importada como src:

tsx
Copiar
<img src={bannerPrincipal} alt="Imagem de Banner Principal" className="banner" />
Aplicar estilos CSS (opcional):

Adicionar a classe .banner no arquivo CSS (por exemplo, App.css) para ajustar a largura, altura e centralização da imagem:

css
Copiar
.banner {
  width: 100%;  /* Ajusta a largura para 100% do contêiner pai */
  max-width: 1000px; /* Limita a largura máxima */
  height: auto; /* Ajusta a altura proporcionalmente */
  margin: 0 auto; /* Centraliza a imagem */
  display: block; /* Garante que a imagem seja tratada como um bloco */
}
Executar o servidor de desenvolvimento:

Verificar se o servidor de desenvolvimento do Vite está em execução com o comando:

bash
Copiar
npm run dev
Verificar se a imagem é carregada corretamente:

Acesse a aplicação no navegador.

Verifique se a imagem foi exibida corretamente, com o tamanho e o estilo aplicados conforme o esperado.

Testar a responsividade (se necessário):

Testar a aplicação em diferentes tamanhos de tela para verificar se a imagem se ajusta corretamente, especialmente se você usou width: 100% ou outras regras de responsividade.

Testar a navegação (se aplicável):

Se a imagem estiver dentro de um link (<a>), como em um banner, verifique se o clique na imagem direciona para a URL correta (por exemplo, https://react.dev).
