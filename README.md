# ⚛️ Tabela Periódica Interativa

Uma aplicação web moderna, responsiva e altamente interativa para a exploração dos elementos químicos. Desenvolvida com uma estética futurista (*dark mode* com detalhes em *neon*), a aplicação foi projetada tanto para o suporte ao estudo acadêmico quanto para a consulta rápida de propriedades químicas essenciais.

🔗 **Acesse a aplicação em tempo real:** [thiagoweslei.github.io/tabelaperiodica/](https://thiagoweslei.github.io/tabelaperiodica/)

---

## 🚀 Recursos Principais

- **Visualização Avançada da Distribuição Eletrônica:** Exibe a configuração eletrônica no estado fundamental (notação de gases nobres) e o detalhamento completo por níveis de energia (K, L, M, N, O, P, Q) baseado no Diagrama de Pauling.
- **Conexão Dinâmica com a Química Orgânica e Inorgânica:** As curiosidades e descrições dos elementos destacam suas aplicações práticas reais, como reagentes de síntese orgânica (ex: reagentes de Grignard, catalisadores de Paládio e Rutênio) e compostos inorgânicos industriais e biológicos.
- **Filtros Inteligentes por Categoria e Estado Físico:** Clique nas legendas para isolar instantaneamente grupos específicos (Metais de Transição, Lantanídeos, Halogênios, etc.) ou estados da matéria (Sólido, Líquido, Gasoso, Desconhecido a 25 °C e 1 atm).
- **Painel Lateral Informativo (*Sidebar*):** Sistema de clique que expande informações aprofundadas sobre o elemento selecionado, incluindo:
  - Símbolo, número atômico e massa atômica precisa (IUPAC).
  - Contagem detalhada de subpartículas (Prótons, Nêutrons e Elétrons).
  - Métodos de obtenção na natureza ou em laboratório.
- **Séries Expansíveis (Lantanídeos e Actinídeos):** Botões integrados na linha 3 do grupo que expandem dinamicamente as séries de transição interna diretamente na estrutura da tabela, otimizando o espaço de tela.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando práticas modernas de desenvolvimento web focado em performance e estilização limpa, sem a necessidade de dependências ou frameworks pesados:

- **HTML5:** Estruturação semântica e layouts robustos.
- **CSS3 (Grid & Flexbox):** Uso intensivo de *CSS Grid* para renderizar com precisão matemática a disposição 18x7 da tabela periódica, além de *CSS Variables* para fácil manutenção da paleta de cores futurista.
- **JavaScript (ES6+ Vanilla):** Manipulação eficiente do DOM, algoritmos para cálculo automatizado de nêutrons e lógica de distribuição eletrônica em tempo de execução.
- **Google Fonts:** Integração das fontes de alta tecnologia *Rajdhani* e *Share Tech Mono*.

---

## 📐 Estrutura do Layout

A tabela utiliza coordenadas de grade estritas para posicionar elementos e componentes informativos integrados:
- **Colunas 4 a 6 / Linhas 2 a 5:** Espaço central otimizado para o *Card de Demonstração (Legenda de Orientação)*.
- **Colunas 7 a 14 / Linhas 2 a 4:** Painel unificado de filtros por Categorias e Estados Físicos.

---

## 🎨 Paleta de Cores e Identidade Visual

A interface adota variáveis de cores semânticas bem definidas para categorizar os elementos de forma intuitiva:

```css
--bg-deep:      #0d0d12; /* Fundo principal escuro */
--accent:       #00e5ff; /* Ciano Neon para destaques e interações */
--c-solid:      #4a9eff; /* Sólidos (🧊) */
--c-liquid:     #ff5252; /* Líquidos (💧) */
--c-gas:        #69f0ae; /* Gasosos (💨) */
--c-unknown:    #777777; /* Sintéticos/Desconhecidos (🌀) */
