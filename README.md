# luz-e-cena
Layout Flexível com Flexbox

Este projeto demonstra o uso das propriedades do CSS Flexbox para criar layouts responsivos e flexíveis. Abaixo estão as propriedades utilizadas e como cada uma delas pode ser aplicada para controlar o layout dos elementos.

<br>

<div style="text-align: center; position: relative; display: inline-block;">
  <!-- Imagem maior -->
  <img src="./images/Banner.png" alt="Imagem Maior" style="width: 80%; max-width: 800px  border-radius: 10px;">




[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


<br>

<h1>Sumário</h1>

<details>
  <summary>🔹 Propriedades flex-box</summary>
  <p>Para usar o Flexbox, definimos o contêiner como flex. Isso permite que seus filhos (itens dentro do contêiner) se comportem como elementos flexíveis.</p>
  <ul>
    <li><code>.container { display: flex; }</code></li>
  </ul>
</details>

<details>
  <summary>🔹 Controlar a Ordem dos Elementos com <code>order</code></summary>
  <p>A propriedade <code>order</code> permite controlar a ordem dos itens dentro de um contêiner flexível. O valor padrão é <code>0</code>. Elementos com valores maiores aparecem depois.</p>
  <ul>
    <li><code>.item { order: 1; }</code></li>
    <li><code>.item2 { order: 2; }</code></li>
  </ul>
</details>

<details>
  <summary>🔹 Ajustar o Crescimento dos Elementos com <code>flex-grow</code></summary>
  <p>A propriedade <code>flex-grow</code> controla o crescimento dos itens dentro de um contêiner flexível. Um item com <code>flex-grow</code> maior vai ocupar mais espaço disponível.</p>
  <ul>
    <li><code>.item { flex-grow: 1; }</code></li>
  </ul>
</details>

<details>
  <summary>🔹 Definir Tamanhos Iniciais com <code>flex-basis</code></summary>
  <p>A propriedade <code>flex-basis</code> define o tamanho inicial de um item antes de o espaço ser distribuído entre os itens flexíveis. O valor pode ser em pixels, porcentagem, etc.</p>
  <ul>
    <li><code>.item { flex-basis: 200px; }</code></li>
  </ul>
</details>

<details>
  <summary>🔹 Alinhar Itens com <code>align-items</code></summary>
  <p>A propriedade <code>align-items</code> alinha os itens ao longo do eixo transversal (geralmente vertical). Pode ter os seguintes valores:</p>
  <ul>
    <li><code>flex-start</code>: Alinha os itens ao topo.</li>
    <li><code>flex-end</code>: Alinha os itens à parte inferior.</li>
    <li><code>center</code>: Alinha os itens ao centro.</li>
    <li><code>stretch</code>: Faz os itens se esticarem para preencher o contêiner.</li>
  </ul>
</details>

<details>
  <summary>🔹 Distribuir Espaço com <code>justify-content</code></summary>
  <p>A propriedade <code>justify-content</code> distribui os itens ao longo do eixo principal (geralmente horizontal). Ela pode ser usada para alterar o espaçamento entre os itens.</p>
  <ul>
    <li><code>flex-start</code>: Alinha os itens ao início do contêiner.</li>
    <li><code>flex-end</code>: Alinha os itens ao final do contêiner.</li>
    <li><code>center</code>: Alinha os itens ao centro.</li>
    <li><code>space-between</code>: Espaço igual entre os itens, sem espaço nas extremidades.</li>
    <li><code>space-around</code>: Espaço igual ao redor dos itens.</li>
  </ul>
</details>

<details>
  <summary>🔹 Controlar Quebra de Linha com <code>flex-wrap</code></summary>
  <p>A propriedade <code>flex-wrap</code> permite que os itens se movam para uma nova linha quando o espaço não for suficiente. Pode ser útil para layouts responsivos.</p>
  <ul>
    <li><code>nowrap</code>: Os itens não quebram a linha (valor padrão).</li>
    <li><code>wrap</code>: Os itens quebram a linha quando necessário.</li>
    <li><code>wrap-reverse</code>: Quebra a linha, mas inverte a ordem dos itens.</li>
  </ul>
  
  <br>

<details>
  <summary>🍿 Veja o Projeto</summary>
  <p>Confira o projeto completo e interativo clicando no link abaixo:</p>
  <a href="URL_DO_SEU_PROJETO" target="_blank">Clique aqui para ver o projeto!</a>
</details>


<details>
  <summary> instrutora </summary>
  <p> Monica Hillman - Alura</p>
</details>






