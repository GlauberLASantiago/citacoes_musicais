# Citações sobre Música

Site interativo para exibir citações musicais aleatórias de forma elegante, com foco em uso educacional. O projeto permite gerar novas coleções de citações, copiar textos rapidamente e obter códigos HTML prontos para incorporação em plataformas como o Moodle.

## Visão geral

O **Citações sobre Música** foi desenvolvido para apresentar frases e pensamentos sobre música de maneira visualmente agradável e prática. A interface busca unir estética, simplicidade e utilidade pedagógica, facilitando o uso das citações em aulas, ambientes virtuais de aprendizagem e materiais didáticos.

## Funcionalidades

- Exibição de **6 citações musicais aleatórias** por coleção  
- Botão para gerar uma **nova coleção**  
- Clique em cada cartão para **copiar a citação**  
- Geração de **código HTML incorporável**  
- Vários temas visuais para embed:
  - Padrão
  - Escuro
  - Minimalista
  - Brutalista
  - Vintage
  - Retro Tech
  - Neon Glow
  - Elegante
- Feedback visual ao copiar conteúdos  
- Interface responsiva com **Tailwind CSS**  
- Integração com **Supabase** para buscar citações aleatórias  

## Tecnologias utilizadas

- HTML5  
- CSS3  
- JavaScript  
- Tailwind CSS  
- Google Fonts  
- Supabase  

## Como funciona

O site consulta uma função RPC no Supabase chamada `obter_citacao_musical_aleatoria`, responsável por retornar uma citação aleatória com texto e autor. A cada carregamento ou clique no botão de nova coleção, o sistema busca 6 citações e monta os cartões dinamicamente na tela.

Além disso, o projeto permite gerar snippets HTML prontos para incorporação externa, usando a mesma fonte de dados para exibir uma citação musical aleatória em outros ambientes.

## Estrutura do projeto

Como o projeto está em um único arquivo, sua estrutura principal é simples:

- `index.html` — contém a estrutura da página, estilos e scripts

## Como usar

1. Clone este repositório:
```
git clone <URL_DO_REPOSITORIO>
```

2. Abra o arquivo `index.html` no navegador.

## Integração com Supabase

O projeto utiliza:

- uma URL de projeto Supabase  
- uma chave pública (`publishable key`)  
- uma função RPC chamada:

```
obter_citacao_musical_aleatoria
```

Essa função deve retornar pelo menos os campos:

- `texto`
- `autor`

## Possíveis melhorias

- Adicionar filtro por autor ou tema  
- Criar busca por palavras-chave  
- Permitir favoritos  
- Adicionar paginação ou histórico de citações exibidas  
- Melhorar acessibilidade  
- Separar HTML, CSS e JS em arquivos diferentes  
- Adicionar instruções automáticas de deploy  

## Público-alvo

Este projeto pode ser útil para:

- professores  
- estudantes  
- pesquisadores  
- ambientes virtuais de aprendizagem  
- páginas educativas sobre música e arte  

## Créditos

Desenvolvido pelo **Professor Glauber Santiago - DAC/UFSCar**.

Links:

- https://servidores.ufscar.br/glauber/  
- https://sites.google.com/view/glauberia  

## Licença

Este projeto pode ser distribuído sob a licença que você escolher. Se desejar, você pode adicionar uma licença MIT para uso aberto.
