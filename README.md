# Triple Espresso da TripleTen

**visualizar projeto:** https://rafaguanciale.github.io/web_project_coffeeshop/

O Coffee Shop foi desenvolvido como parte da Sprint 4 do curso de Web Development da TripleTen.
Este projeto marca um ponto importante da jornada, pois é onde a estrutura do código começa a ficar realmente profissional:

- Uso de CSS modularizado
- Metodologia BEM aplicada de verdade
- Formulários
- Prática real com iframes
- Flexbox para layout
- Organização e limpeza do CSS
- Arquitetura de pastas que prepara o caminho para projetos maiores.

A Sprint 4 representou uma transição clara entre “aprender tags” e construir páginas com pensamento de desenvolvedor, organizando blocos, mantendo consistência e evitando confusão no CSS.

## Tecnologias Utilizadas

- HTML5
- CSS3
- Flexbox
- Position (relative, absolute)
- Animações com @keyframes
- Transições em links (transition: opacity)
- Metodologia BEM
- Responsividade parcial
- Arquitetura modular de CSS conforme a BEM

## Principais Funcionalidades e Soluções Técnicas

1. Header com layout flexível

- Estrutura semântica usando BEM (header, header**title, header**image, etc.)
- Imagem posicionada com position: absolute
- Título com destaque estilizado
- Layout preenchendo 100vh com limites de altura para telas menores

2. Seção Recipes com vídeos incorporados

- Uso de iframes para exibir vídeos externos
- Bloco organizado com BEM (recipes, recipes**videos, recipes**iframe, etc.)
- Layout flexbox com espaçamento consistente
- Títulos e subtítulos com tipografia serifada para contraste visual

3. Formulário da seção Reservation

- Formulário completo estilizado com CSS
- Estrutura BEM: form, form**label, form**input, form\_\_button
- Inputs alinhados verticalmente com espaçamento consistente
- Foco (focus) e hover com feedback visual leve
- Arquivo CSS separado especificamente para o bloco de formulário

4. Arquitetura de CSS modular

- Cada bloco com seu próprio arquivo (header.css, recipes.css, reservation.css, etc.)
- page.css com estilos globais (fonte, largura, reset básico)
- Separação de responsabilidades clara e escalável

## Aprendizados Pessoais

Este projeto me mostrou que organizar o código é tão importante quanto fazê-lo funcionar.
Alguns aprendizados que consolidaram minha base:

- BEM não é só nome: é estrutura, separação, clareza e previsibilidade do CSS
- Como dividir estilos em arquivos realmente melhora o fluxo de trabalho
- Como criar blocos reutilizáveis sem acoplar tudo ao mesmo arquivo
- Como pensar em layout com Flexbox para evitar posicionamentos artificiais
- Como formular um design consistente entre seções diferentes
- Importância de evitar poluição global de CSS e classes genéricas sem propósito

A Sprint 4 também marcou a fase em que comecei a pensar como dev, não só cumprir tarefas.
Cada detalhe do CSS e do HTML passou a vir com uma intenção mais clara.

## Melhorias Futuras

- Tornar o layout totalmente responsivo
- Inserir validação de formulário com JavaScript (próximas sprints)
- Adicionar animações leves em elementos-chave

## Screenshots

Página completa
![page](./images/cafe_triple_espresso.jpg)
