---
name: ui-design-system
description: Criação e manutenção de sistemas de design para interfaces de usuário. Use para: padronizar componentes, definir tokens de design (cores, tipografia, espaçamento) e garantir consistência na UI.
---

# UI Design System Skill

Esta skill fornece diretrizes para a criação e manutenção de sistemas de design (Design Systems) robustos, garantindo consistência, escalabilidade e eficiência no desenvolvimento de interfaces de usuário.

## Componentes Essenciais de um Design System

1. **Tokens de Design (Design Tokens)**
   - Variáveis que armazenam valores visuais fundamentais.
   - **Cores**: Primárias, secundárias, neutras, semânticas (sucesso, aviso, erro).
   - **Tipografia**: Famílias de fontes, tamanhos (escalas), pesos, alturas de linha.
   - **Espaçamento**: Escalas baseadas em um valor base (ex: 4px ou 8px).
   - **Bordas**: Raios (border-radius), larguras e estilos.
   - **Sombras**: Elevações para criar profundidade.

2. **Biblioteca de Componentes (Component Library)**
   - Elementos de interface reutilizáveis construídos a partir dos tokens.
   - **Átomos**: Botões, inputs, ícones, tipografia base.
   - **Moléculas**: Grupos de átomos (ex: um campo de busca com input e botão).
   - **Organismos**: Grupos de moléculas (ex: um cabeçalho de navegação completo).
   - **Templates/Páginas**: Estruturas de layout completas.

3. **Diretrizes de Uso (Guidelines)**
   - Documentação sobre *como* e *quando* usar cada componente.
   - Estados de componentes (default, hover, active, disabled, focus).
   - Regras de acessibilidade (contraste, navegação por teclado, ARIA labels).
   - Padrões de redação (UX Writing) para mensagens de erro, tooltips, etc.

## Princípios de Construção

- **Atomic Design**: Metodologia (criada por Brad Frost) que divide a interface em componentes menores e reutilizáveis (Átomos, Moléculas, Organismos, Templates, Páginas).
- **Acessibilidade First**: Componentes devem ser acessíveis desde a concepção (WCAG).
- **Flexibilidade e Extensibilidade**: O sistema deve permitir adaptações sem quebrar a consistência global.
- **Nomenclatura Semântica**: Nomeie tokens pelo seu *propósito*, não pelo seu *valor* (ex: use `color-primary` em vez de `color-blue`).

## Instruções de Uso

1. **Auditoria Visual**: Antes de criar, analise as interfaces existentes para identificar padrões inconsistentes.
2. **Definição de Tokens Base**: Comece definindo a paleta de cores, escala tipográfica e sistema de espaçamento.
3. **Criação de Átomos**: Desenvolva os componentes mais básicos (botões, inputs de texto).
4. **Documentação Simultânea**: Documente cada componente assim que for criado, incluindo estados e exemplos de uso.
5. **Composição (Moléculas e Organismos)**: Combine os átomos para formar componentes mais complexos.
6. **Revisão e Teste**: Teste os componentes em diferentes contextos e dispositivos para garantir responsividade e acessibilidade.
7. **Evolução Contínua**: Um Design System é um produto vivo; atualize-o conforme as necessidades do projeto evoluem.
