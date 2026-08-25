# **Space-Survivor**

## Desenvolvedor

**Nome:** Jessia Fernandes Guimarães
**Turma:** 2º Ano TEC — Desenvolvimento de Sistemas  
**Instituição:** SENAI  
**Ano:** 2026

## Sobre o projeto

"Space Survivor" é um jogo de ação espacial frenético! No comando de uma nave solitária, você enfrenta hordas neon de inimigos em um combate estilo "bullet hell". Use impulsos rápidos para desviar, evolua suas armas a cada nível e colete "power-ups" devastadores para derrotar chefes colossais. Sobreviva e supere seus limites!

### Objetivo do Projeto

O objetivo foi analisar o código-fonte de um jogo existente, compreender seu funcionamento e realizar modificações utilizando conceitos de desenvolvimento de sistemas.

Após as alterações, o projeto foi publicado no GitHub e disponibilizado por meio do GitHub Pages.

## Tecnologias

- **HTML5:** Utilizado para estruturar a página e prover o elemento Canvas onde o jogo é renderizado.
- **CSS3:** Responsável pela estilização visual do projeto, incluindo menus, HUD e responsividade para dispositivos móveis.
- **JavaScript:** Utilizado para programar toda a lógica do jogo, controle de estados, física, sistema de ondas e gerenciamento de pontuação.
- **Canvas API:** Empregada para fazer a renderização gráfica 2D em tempo real, lidando com os desenhos das naves, tiros, partículas e animações a 60 FPS.
- **Web Audio API:** Utilizada para a criação e reprodução de efeitos sonoros sintetizados em tempo real, sem a necessidade de carregar arquivos externos de áudio.
- **GitHub:** Usado para versionamento de código e hospedagem do repositório do projeto.
- **GitHub Pages**: Plataforma utilizada para publicar e disponibilizar o jogo online de forma gratuita.

- **Diferencial do Projeto:** Funciona 100% no navegador dentro de um único arquivo otimizado, sem a necessidade de bibliotecas externas, oferecendo alta performance gráfica, efeitos de som dinâmicos por código e suporte completo a telas sensíveis ao toque (Mobile).

## Instalação e USo

Você pode jogar diretamente pelo navegador sem precisar instalar nada no computador. Para rodar o projeto localmente, siga os passos:

- Baixe o arquivo SpaceSurvivor-Melhorado2.0.html deste repositório.

- Dê um duplo clique no arquivo baixado para abri-lo no seu navegador de preferência (Google Chrome, Edge, Firefox, etc.).

- Clique na tela e divirta-se!

### Como jogar

#### Computador

| Ação    | Controle |
|---|---  |

| Mover   | W, A, S, D ou setas |
| Mirar   | Mouse (Automático) |
| Impulso | Espaço |
| Pausar  | P |

### Celular

**-Movimentação e Direção:** Arraste o dedo em qualquer lugar da tela para controlar a nave via joystick virtual.

**Miras e Disparos:** A nave mira e atira automaticamente nos inimigos mais próximos.


## Modificações realizadas

- **Otimização de Performance:** Remoção de efeitos pesados de processamento (shadowBlur e shadowColor do Canvas) e ajuste no loop de colisão entre inimigos para eliminar travamentos e manter a taxa de quadros estável (60 FPS).

- **Organização e Limpeza de Código:** Reestruturação do script JavaScript, centralização das variáveis CSS para fácil customização visual e refatoração da lógica de reset e inicialização do jogo.

- **Controle de Memória:** Limitação na quantidade máxima de partículas e textos flutuantes gerados simultaneamente na tela para evitar vazamentos de memória em partidas longas.

- **Ajustes de Balanceamento:** Reajuste dos pontos de vida inicial da nave, velocidade dos projéteis, cadência dos tiros e limite máximo de inimigos em tela para garantir uma curva de dificuldade mais justa e progressiva.

