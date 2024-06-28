# PlayerJoin Plugin

**PlayerJoin** é um plugin para Minecraft desenvolvido para exibir mensagens no chat sempre que um jogador entra ou sai do servidor. Este plugin é ideal para servidores que desejam manter seus jogadores informados sobre quem está online.

## Funcionalidades

- Exibe uma mensagem no chat quando um jogador entra no servidor.
- Exibe uma mensagem no chat quando um jogador sai do servidor.
- Mensagens personalizáveis através de um arquivo de configuração.

## Instalação

1. Baixe a versão mais recente do plugin PlayerJoin.
2. Coloque o arquivo `.jar` do plugin na pasta `plugins` do seu servidor Minecraft.
3. Reinicie o servidor para que o plugin seja carregado.

## Configuração

Após a primeira execução do plugin, um arquivo de configuração `config.yml` será gerado na pasta `plugins/PlayerJoin`. Você pode editar este arquivo para personalizar as mensagens exibidas quando um jogador entra ou sai do servidor.

### Exemplo de `config.yml`

```yaml
# Mensagem exibida quando um jogador entra no servidor
joinMessage: "&a[PlayerJoin] &e{player} entrou no servidor!"

# Mensagem exibida quando um jogador sai do servidor
quitMessage: "&c[PlayerJoin] &e{player} saiu do servidor!"
