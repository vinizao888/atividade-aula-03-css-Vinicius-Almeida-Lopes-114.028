# atividade-aula-03-css-Vinicius-Almeida-Lopes-114.028

## Tema da página
A página representa a **TechVerde**, um projeto fictício focado em tecnologia e soluções sustentáveis para o meio ambiente.

## Cores escolhidas
- **Branco (`white`):** Usado no fundo principal da página (`body`).
- **Verde (`green`):** Usado no fundo do cabeçalho (`header`) e dos cards de conteúdo (`.card`).
- **Verde Limão e Amarelo (`greenyellow` e `yellowgreen`):** Usados no fundo do rodapé (`footer`) e no título da seção de serviços.
- **Azul (`royalblue`):** Usado na borda dos cards.
- **Cinza e Branco Claro (`grey` e `whitesmoke`):** Usados na borda da imagem e no título da seção "Sobre".

## Seletores utilizados
- **Seletor por Tag:** `body`, `header`, `main`, `footer`, `nav a`.
- **Seletor por Classe:** `.card` e `.imagem-destaque`.
- **Seletor por ID:** `#sobre` e `#servicos`.

## Onde foram aplicados margin, padding e border
- **Margin:** Aplicado nos cards (`margin-bottom: 20px`), nos títulos, na imagem e para centralizar o bloco principal na tela (`margin: 20px auto`).
- **Padding:** Aplicado no cabeçalho (`padding: 20px`), no rodapé (`padding: 15px`), dentro dos cards (`padding: 15px`) e nos links do menu (`padding: 5px`).
- **Border:** Aplicado ao redor dos cards (`border: 3px solid royalblue`) e na imagem do projeto (`border: 5px solid grey`).

## Como o box model foi utilizado
O Box Model foi ativado no topo do arquivo CSS com o seletor universal `* { box-sizing: border-box; margin: 0; padding: 0; }`. Isso garante que as bordas e os espaçamentos internos fiquem embutidos no tamanho total dos blocos, evitando que o layout quebre.

## Uma dificuldade encontrada e como ela foi resolvida
- **Dificuldade:** Fazer com que a imagem se ajustasse corretamente dentro do card sem ultrapassar os limites laterais.
- **Solução:** Aplicação das propriedades `width: 100%;` e `max-width: 100%;` na classe `.imagem-destaque`, fazendo a imagem acompanhar o tamanho da caixa .
