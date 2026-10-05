# Organizador de Estudos

Aplicação web de página única para organizar estudos universitários com técnicas baseadas em evidência. Um único arquivo HTML, sem backend e sem instalação: os dados ficam salvos no navegador (localStorage).

## Funcionalidades

- **Painel "Hoje"**: cartão de Próximo passo com botão Começar/Retomar e retomada exata de onde você parou
- **Captura inteligente**: digite em texto livre ("estudei Direito Civil das 19h às 21h") e o app organiza cada item na aba certa (sessão, ideia, erro ou revisão)
- **Matérias**: status automático pela Regra dos 85% (zona ideal de dificuldade)
- **Cronograma semanal**: blocos de estudo por dia e horário, com bloco semanal de intercalamento (Set Misto)
- **Sessões**: registro de questões e acertos com JOL atrasado e cálculo do gap de calibração
- **Exercícios IA**: o app monta um prompt para a Adapta ONE gerar questões; você importa a resposta e pratica dentro do app
- **Caderno de erros**: foco em erros de alta confiança ("jurava que sabia"), que entram direto na revisão prioritária
- **Revisão espaçada**: ciclo simplificado de 1, 3, 7, 14 e 30 dias
- **Guia**: como fazer bons flashcards, com exemplos antes/depois e checklist

## Acessibilidade para TDAH

- Navegação em três destinos (Hoje, Estudar, Organizar) com captura global em qualquer tela
- Modo foco durante sessões, com timer de 25 minutos opcional (desligado por padrão)
- Modo calmo que esconde contadores e indicadores que geram sobrecarga
- Preferências: tema claro/escuro, densidade, tamanho de texto, redução de movimento e abas ocultáveis
- Feedback imediato em toda ação, contraste mínimo 4,5:1, alvos de toque de 44px e navegação por teclado

## Técnicas incorporadas

Reaprendizagem sucessiva, Regra dos 85%, JOL atrasado, pré-teste, intercalamento com discriminação, error log de alta confiança (hipercorreção), revisão espaçada, NSDR e revisão pré-sono. Cada técnica tem um guia rápido dentro do app.

## Como usar

1. Baixe o arquivo `index.html`
2. Abra em qualquer navegador moderno (desktop ou celular)
3. Opcional: clique em "Carregar exemplo" para explorar o app com dados fictícios

## Publicar no GitHub Pages

1. Crie um repositório com o nome `seuusuario.github.io`
2. Faça upload do `index.html` na raiz do repositório
3. Em Settings → Pages, selecione a branch `main` e a pasta `/(root)`, depois salve
4. Em alguns minutos, o app estará disponível em `https://seuusuario.github.io/`

## Privacidade

Todos os dados ficam no localStorage do seu navegador. Nada é enviado a servidores. Os dados não sincronizam entre dispositivos ou navegadores.

## Tecnologias

HTML, CSS e JavaScript puros em um único arquivo autocontido, sem dependências externas obrigatórias.

## Licença

MIT
