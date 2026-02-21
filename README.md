# ⚜ Gerador de Cardápio Semanal — Le Cordon Bleu ⚜

Um aplicativo progressivo para Web (PWA) de planejamento e gerador de refeições semanais inspirado na estética e no requinte da tradicional escola de culinária francesa, **Le Cordon Bleu**. Este aplicativo é utilizado para organizar o cardápio doméstico de almoços e jantares, evitando desperdícios e repetitividade, além de criar listas de compras automáticas de supermercado com as porções idealizadas.

## 🌟 Principais Características do Projeto

O sistema conta com as opções principais: **🥩 Carnes**, **🍝 Prato Principal**, **🍚 Acompanhamento** e **🥗 Salada**. E opera através de dezenas de utilidades em seu núcleo, tais como:

### 1. Sistema Antibanalização
O gerador garante que o **mesmo prato não se repita** ao longo da mesma semana. Ele analisa os pratos já sorteados e faz re-rolagens automáticas ou manuais preservando a diversidade para os próximos dias da semana.

### 2. Domingos em Modo "Almoço Pronto" (Folga)
Para dar descanso a vida culinária, o projeto contém um relógio de ponto logístico que detecta através de um épico intermitente (Iniciado em **01/03/2026**). A cada **duas semanas**, o Domingo receberá a indicação unânime de **Almoço Pronto** e não indicará afazeres.

### 3. Gerador Automático de Lista de Compras
Após rodar o planejamento da semana, o sistema calcula autonomisticamente as medidas de cada ingrediente (Feijão, Arroz, Legumes, Carnes) baseadas no número de pessoas na casa (hoje calibrado para 2), totalizando o volume em **Kilos** ou **Litros** a se comprar e evitando compras excessivas ou insuficientes no mercado.

### 4. Gestão e Exportação
*   **Recarregamento Fiel:** Ao ser reaberto, o usuário será direcionado ao último cardápio gravado devido à comunicação ativa via **LocalStorage** do navegador.
*   **Compartilhamento e Arquivos (Export):** Pode-se baixar a semana inteira num arquivo **.html** super enxuto e estático de tamanho mínimo, que qualquer outra pessoa – ou até mesmo a si próprio – pode arquivar para carregar futuramente na plataforma pela opção **📂 Abrir Arquivo** do próprio programa.
*   **WhatsApp Integrado:** Gera sumários textuais com as listas de compras aglomeradas no final, lançando a cópia pronta diretamente no aplicativo do WhatsApp em um toque.

### 5. Estética Premium (UI)
As cores foram inspiradas em conceitos culinários sofisticados:
*   Navy e Gold para o cabeçalho e tipografias elegantes baseadas no layout do Le Cordon Bleu.
*   Background dinâmico com padrões de micro-animações (Dotted Arrays).
*   Tipografias cursivas e garifas (Playfair Display) contrapostas a fontes claras (Lato).

---

## 💻 Tecnologias

*   **HTML5, JS e CSS3 (Vanilla System):** O código é feito de forma independente usando flexível sistema grid e de tipologias Vanilla sem inchaços ou bibliotecas pesadas de terceiros (Tailwind, BootStrap).
*   **PWA (`manifest.json` & `sw.js`):** Arquitetado como um Progressive Web Application instalável por via de abas de navegador mobile, onde simulará um aplicativo enraizado. 

---

## 🔎 Como Encontrar no GitHub

Este projeto já encontra-se abrigado, gerido em controle de versão e persistido remotamente no GitHub através de suas chaves e credenciais, e pode ser visitado pelo repositório em:

[**https://github.com/paulopalaoro/Cardapio.git**](https://github.com/paulopalaoro/Cardapio.git)

O usuário pode simplesmente baixar (Clone), inspecionar as ramificações de modificações, acompanhar seu histórico de modificações para o Escondidinho e as Carnes, na *Branch principal (main)*.

### 🌐 Testando e Usando Online (Browser)

O Cardápio também possui o seu endereço persistido através do GitHub Pages, podendo ser rodado na web e salvo como PWA para os celulares Android e iOS, no endereço oficial através deste link:

[**https://paulopalaoro.github.io/Cardapio/Le_menu.html**](https://paulopalaoro.github.io/Cardapio/Le_menu.html)
