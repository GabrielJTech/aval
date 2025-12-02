<h1> Aplicação dos Princípios de IHM na Interface PROESP-Br</h1>

<h2> Sumário</h2>
<ul>
  <li><a href="#objetivo">1. Objetivo da Interface</a></li>
  <li><a href="#estrutura">2. Estrutura da Interface</a></li>
  <li><a href="#principios">3. Aplicação dos Princípios de IHM</a></li>
  <li><a href="#conclusao">4. Conclusão</a></li>
</ul>

<hr>

<h2 id="objetivo"> 1. Objetivo da Interface</h2>

<p>
A aplicação foi desenvolvida para simular o processo de avaliação física descrito no 
<b>Manual PROESP-Br</b>, organizando o fluxo de interação em até <b>três telas</b>.
O projeto aplica princípios de <b>Interação Humano-Máquina (IHM)</b> com o intuito de:
</p>

<ul>
  <li>Garantir eficiência e fluidez na entrada de dados</li>
  <li>Organizar a navegação de forma lógica e intuitiva</li>
  <li>Minimizar erros do usuário por meio de validação e feedback</li>
  <li>Fornecer consistência visual e responsividade</li>
  <li>Melhorar compreensão e tomada de decisão durante o preenchimento</li>
</ul>

<p>
A estrutura é composta por duas telas funcionais e uma tela de resumo, atendendo às regras de simplicidade e baixo esforço cognitivo.
</p>

<hr>

<h2 id="estrutura"> 2. Estrutura da Interface</h2>

<h3> Tela 1 – Identificação e Triagem (PAR-Q)</h3>
<ul>
  <li>Campos pessoais: nome, idade, sexo e escola</li>
  <li>PAR-Q simplificado com <b>5 perguntas binárias</b></li>
  <li>Validação imediata com cores e mensagens</li>
  <li>Organização vertical para leitura natural</li>
</ul>

<h3> Tela 2 – Antropometria + Testes Motores</h3>
<ul>
  <li>Coleta de peso, altura e cálculo automático de IMC</li>
  <li>Testes de força, flexibilidade, velocidade, resistência e potência</li>
  <li>Agrupamento visual por categorias seguindo Gestalt</li>
  <li>Caixas destacadas para facilitar distinção entre testes</li>
</ul>

<h3> Tela 3 – Resumo Final</h3>
<ul>
  <li>Exibe todos os dados informados pelo usuário</li>
  <li>Nenhum campo editável para evitar erros finais</li>
  <li>Botão para reiniciar todo o processo</li>
  <li>Permite validar a entrada completa antes de enviar</li>
</ul>

<hr>

<h2 id="principios"> 3. Aplicação dos Princípios de IHM</h2>

<h3> 3.1. Lei de Fitts – Alvos maiores e próximos</h3>
<p>
A Lei de Fitts estabelece que a velocidade e precisão de um movimento dependem do tamanho e distância do alvo.
</p>

<p><b>Aplicações práticas:</b></p>
<ul>
  <li>Botões amplos (próximos e de fácil acesso)</li>
  <li>Inputs ocupando 100% da largura para toque preciso</li>
  <li>Elementos essenciais próximos, reduzindo deslocamento do cursor</li>
  <li>Barras e caixas alinhadas verticalmente</li>
</ul>

<p><b>Benefício:</b> reduz esforço motor, acelera a interação e aumenta a precisão do usuário — especialmente em dispositivos móveis.</p>

<hr>

<h3> 3.2. Lei de Hick-Hyman – Redução da carga cognitiva</h3>
<p>
Segundo a lei, quanto maior o número de opções simultâneas, maior o tempo de decisão.
</p>

<p><b>Aplicações práticas:</b></p>
<ul>
  <li>Formulário dividido em <b>etapas</b>: Identificação → Testes → Resumo</li>
  <li>Cada tela contém apenas informações essenciais</li>
  <li>A última tela não exige decisões — apenas leitura</li>
</ul>

<p><b>Benefício:</b> decisões mais rápidas, menos confusão e melhor fluidez.</p>

<hr>

<h3> 3.3. Princípios da Gestalt – Organização visual</h3>

<ul>
  <li><b>Proximidade:</b> campos semelhantes agrupados em blocos</li>
  <li><b>Similaridade:</b> inputs com o mesmo estilo, forma e cor</li>
  <li><b>Continuidade:</b> fluxo vertical contínuo e previsível</li>
  <li><b>Figura-fundo:</b> caixas agrupadas com fundo levemente destacado</li>
</ul>

<p><b>Benefício:</b> maior clareza, leitura natural e compreensão imediata dos grupos de informação.</p>

<hr>

<h3> 3.4. Prevenção de Erros – Princípio de Shneiderman</h3>

<p><b>Aplicações práticas:</b></p>
<ul>
  <li>Validação numérica (mínimo e máximo)</li>
  <li>Mensagens de erro exibidas instantaneamente</li>
  <li>Campos obrigatórios antes de prosseguir</li>
  <li>Evita erro de cálculo gerando o IMC automaticamente</li>
</ul>

<p><b>Benefício:</b> evita entradas inválidas antes de ocorrerem, reduzindo retrabalho.</p>

<hr>

<h3> 3.5. Feedback Imediato – Heurística de Nielsen</h3>
<p>
Feedback rápido mantém o usuário ciente do estado do sistema.
</p>

<p><b>Aplicações práticas:</b></p>
<ul>
  <li>PAR-Q muda de cor conforme resposta (verde/vermelho)</li>
  <li>Classificação do IMC com cores automáticas</li>
  <li>Mensagens de erro exibidas enquanto digita</li>
  <li>Resumo final contendo todos os dados inseridos</li>
</ul>

<p><b>Benefício:</b> reduz incertezas e orienta a ação correta.</p>

<hr>

<h3> 3.6. Acessibilidade</h3>

<p><b>Aplicações práticas:</b></p>
<ul>
  <li>Navegação completa por teclado</li>
  <li>Boa hierarquia visual e contraste adequado</li>
  <li>Layout responsivo para celulares</li>
  <li>Botões com indicação de foco visível</li>
</ul>

<p><b>Benefício:</b> garante acesso a diferentes perfis de usuários e dispositivos.</p>

<hr>

<h3> 3.7. Tela de Resumo – Revisão final</h3>

<p><b>Aplicações:</b></p>
<ul>
  <li>Apresentação limpa e organizada de todos os dados</li>
  <li>Confirmação antes de finalizar</li>
  <li>Nenhuma ação extra é pedida</li>
</ul>

<p><b>Benefício:</b> elimina erros finais e aumenta a confiabilidade da coleta.</p>

<hr>

<h2 id="conclusao"> 4. Conclusão</h2>

<p>
A interface aplica os principais princípios de IHM — Fitts, Hick-Hyman, Gestalt, 
prevenção de erros, feedback imediato e acessibilidade — resultando em uma experiência 
clara, organizada e eficiente. O sistema segue o limite de três telas e 
prioriza simplicidade, precisão e apoio visual ao usuário.
</p>
