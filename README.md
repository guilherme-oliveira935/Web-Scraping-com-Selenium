# Projeto Automação Web - Busca de Preços

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/guilherme-oliveira935/Web-Scraping-com-Selenium/blob/main/LICENSE)

## Objetivo: Treinar um projeto em que seja necessário utilizar automações web para buscar informações

## Descrição:

Imagine que uma pessoa trabalhe na área de compras de uma empresa e precisa fazer uma comparação de fornecedores para os seus insumos/produtos. Diante disso, ela precisa constantemente buscar nos sites desses fornecedores os produtos disponíveis e o preço, afinal, cada um deles pode fazer promoção em momentos diferentes e com valores diferentes.

objetivo: Se o valor dos produtos for abaixo de um preço limite definido, descobrir os produtos mais baratos e atualizar isso em uma planilha.
Em seguida, vai enviar um e-mail com a lista dos produtos abaixo do seu preço máximo de compra.

### Comentários:
- Nesse projeto usaremos o google shopping e o buscapé, pois outros sites de compra possuem certos meios de bloquear web scraping.
- Os elementos html foram pegos, em sua maioria, pela classe do elementos, o que normalmente é algo que permanece igual mesmo que o site passe por mudanças. Ainda sim, dependendo da data que este código executada, certos erros podem aparecer por consequência de mudanças nos sites em questão.
- É possível utilizar as APIs dos sites para executar a mesma tarefa, mas não é o objetivo desse projeto.
- O script está desenvolvido em jupyter para facilitar o entendimento, para executar todo o processo de uma vez, basta colar as linhas de códigos na sequência das células em um .py
- A faixa de preço pode fazer com que a lista de resultados seja bem diferente dependendo da data, por isso, vale a pena dar uma olhada e decidir se a faixa de valores fazem sentido no contexto do momento.
- O script já "baixa" o ultimo driver do navegador utilizado (Chrome) durante a execução
- Recomendo que utilize o Google Chrome como navegador padrão durante a execução.
  
## Material disponível:
- Planilha com:
  - Nome dos produtos;
  - Preço mínimo: Pode não fazer sentido de primeira vista, pois quanto menor, melhor. Mas isso serve como um parâmetro adicional para evitar que produtos totalmente fora do objetivo ou de fonte claramente duvidosa sejam armazenados;
  - Preço máximo;
  - Termos banidos: palavras que frequentemente aparecem junto com o nome dos produtos, mas que designam outro produto ou palavras que designam características que não nos interessam, como marca, tamanho, cor etc;

## Tecnologias utilizadas
- Python 3
- Biblioteca Pandas
- Biblioteca Selenium
- Biblioteca win32

## Como executar o projeto
- instalar as bibliotecas mencionadas;
- Ter o outlook baixado no seu computador;
- Clonar esse repositório;
- Mudar as linhas de códigos indicadas no arquivo projeto.ipynb para o devido caminho dos diretórios;

### Autor:
Guilherme Oliveira
