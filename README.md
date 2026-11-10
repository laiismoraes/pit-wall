# 🏎️ Pit Wall — GP de São Paulo 🏁

Projeto de recriação da página oficial do **GP de São Paulo de F1** utilizando apenas **HTML5 e CSS3 puro**, desenvolvido como atividade da disciplina de Linguagem de Marcação (LIMA).

---

## 🎯 Sobre o Projeto

O objetivo principal desta aplicação é consolidar conceitos avançados de estruturação web e estilização moderna sem o uso de frameworks externos. A interface foi construída com base no design fornecido em aula, garantindo fidelidade visual e alta performance tanto em computadores quanto em dispositivos móveis.

---

## 🛠️ Tecnologias e Recursos Utilizados

- **HTML5:** Estruturação semântica da página (`header`, `main`, `section`, `form`, `table`, `footer`).
- **CSS3:**
  - **Variáveis (`:root`):** Centralização da paleta de cores e temas das equipes de F1.
  - **Flexbox:** Alinhamento dinâmico da barra superior (`topbar`), botões e filtros.
  - **CSS Grid & `auto-fit`:** Layout responsivo dos cards dos pilotos e divisão do formulário.
  - **Gradientes & Efeitos:**
    - Degradê com corte seco para a faixa inclinada da seção *Hero*.
    - `repeating-linear-gradient` para a estilização da zebra da pista.
    - Efeito *hover* com transições suaves nos cards, botões e linhas da tabela.
  - **Media Queries (`@media`):** Layout 100% responsivo para telas móbiles (smartphones e tablets).
- **Google Fonts:** Tipografia oficial utilizando a fonte *Titillium Web*.

---

## 📁 Estrutura de Arquivos

```text
pit-wall/
├── index.html        # Estrutura HTML principal
├── styles.css        # Estilização completa e responsividade
└── img/
    └── piloto.jpg    # Imagem de fundo da seção Hero
