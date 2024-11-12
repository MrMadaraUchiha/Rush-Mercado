# RUSH-Mercado.v2

**RUSH-Mercado.v2** é o substituto ideal do BlackMarket para servidores Minecraft! Este plugin de mercado oferece uma maneira simples e customizável para jogadores comprarem e venderem itens em um ambiente seguro e balanceado. Com ele, os jogadores podem criar suas próprias lojas, definir preços, e gerenciar suas vendas, proporcionando uma economia dinâmica e colaborativa.

## 📜 Características

- **Mercado de Jogadores**: Permite que os jogadores estabeleçam lojas no mercado, oferecendo seus itens a outros jogadores.
- **Configuração de Taxas e Comissões**: Administradores podem definir taxas sobre as vendas para manter o equilíbrio da economia.
- **Sistema de Preços Controlados**: Limite de preços máximos e mínimos para evitar inflação e desvalorização de itens.
- **Interface Amigável**: Layout simples e intuitivo, facilitando a navegação e o uso por jogadores de todos os níveis.
- **Logs de Transações**: Todas as vendas e compras são registradas, permitindo um monitoramento detalhado por parte dos administradores.
- **Compatibilidade**: Compatível com as principais versões do Minecraft e outros plugins de economia.

## 📦 Instalação

1. **Baixe o plugin** e coloque o arquivo `.jar` na pasta `plugins` do seu servidor Minecraft.
2. Reinicie o servidor para que o plugin seja carregado.
3. Configure o plugin no arquivo `config.yml` para ajustar taxas, permissões e outras opções.

## ⚙️ Configuração Básica

No arquivo `config.yml`, você poderá definir:

- **Taxas de Venda**: Defina uma porcentagem que será cobrada em cada transação.
- **Limite de Preços**: Estabeleça limites mínimo e máximo para itens específicos.
- **Permissões**: Controle quem pode criar lojas, definir preços e acessar o mercado.

## 📖 Comandos Principais

- `/mercado` - Abre a interface do mercado.
- `/mercado listar` - Lista os itens à venda pelo jogador.
- `/mercado vender <preço>` - Coloca o item em sua mão à venda pelo preço especificado.

## 🔑 Permissões

- `rushmercado.use` - Permite ao jogador acessar o mercado.
- `rushmercado.sell` - Permite ao jogador colocar itens à venda.
- `rushmercado.admin` - Acesso total para configurações e gerenciamento do mercado.

## 🛠 Suporte

Caso precise de ajuda ou tenha sugestões, visite nosso tópico oficial no [GamersBoard](https://gamersboard.com.br/topic/50297-rush-mercado-o-seu-substituto-do-blackmarket/) ou abra uma issue aqui no GitHub.

## 📜 Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

### Créditos

Este projeto foi desenvolvido por **[Eduardo Mior](https://github.com/eduardo-mior)**. Agradecemos pela contribuição no desenvolvimento deste plugin incrível!

### Exemplo de Configuração

```yaml
market:
  tax: 5.0 # Taxa de 5% sobre as vendas
  min_price: 10 # Preço mínimo para itens
  max_price: 1000 # Preço máximo para itens
