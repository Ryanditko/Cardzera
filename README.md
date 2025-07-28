
Substitua `:serverId` pelo ID do seu servidor do Discord.

> **Dica:**  
> Para obter o ID do seu servidor: Ative o Modo Desenvolvedor > Clique com o direito no servidor > Copiar ID

Exemplo de uso no README:

```markdown
[![Card do Discord](https://cardzera.audibert.dev/api/:serverId?t={timestamp})](https://discord.gg/serverInviteCode)
```

## Exemplos ao vivo

### Teyvat
[![Card do Discord](https://cardzera.audibert.dev/api/748720691645251716?t={timestamp})](https://discord.gg/gibrasil)


> **IMPORTANTE:**  
> Adicionar `?t={timestamp}` na URL é essencial para forçar a atualização do card em tempo real.

## Parâmetros

Você pode customizar seu card adicionando os seguintes parâmetros na URL:

| Parâmetro             | Padrão   | Descrição                                         |
| --------------------- | -------- | ------------------------------------------------- |
| `backgroundColor`     | `1a1c1f` | Cor de fundo do card                              |
| `buttonColor`         | `00863A` | Cor do botão de entrar                            |
| `buttonText`          | `Join`   | Texto do botão (máx. 28 caracteres)               |
| `buttonTextColor`     | `ffffff` | Cor do texto do botão                             | 
| `buttonBorderRadius`  | `10`     | Raio da borda do botão em pixels (mín: 0, máx: 30)|
| `infoColor`           | `b5bac1` | Cor das informações (membros/online)              |
| `nameColor`           | `ffffff` | Cor do nome do servidor                           |
| `borderRadius`        | `10`     | Raio da borda do card em pixels (mín: 0, máx: 30) |

#### Exemplo com todos os parâmetros:

```markdown
[![Card do Discord](https://cardzera.audibert.dev/api/:serverId?backgroundColor=ffffff&buttonColor=000000&buttonBorderRadius=0&buttonText=Star%20the%20repository&buttonTextColor=ffffff&infoColor=353535&nameColor=000000&borderRadius=0&t={timestamp})](https://discord.gg/serverInviteCode)
```

#### Saída:

[![Card do Discord](https://cardzera.audibert.dev/api/1383718526694461532?backgroundColor=ffffff&buttonBorderRadius=10&buttonColor=000000&buttonText=Star%20the%20repository&buttonTextColor=ffffff&infoColor=353535&nameColor=000000&borderRadius=0&t={timestamp})](https://discord.gg/XuhsaMEqzf)

> **Nota:**  
> Se o servidor não tiver foto, uma imagem padrão será usada.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request se tiver sugestões de melhorias.

Certifique-se de que sua sugestão é relevante e que você testou o app localmente antes de enviar um pull request.

## Suporte

_Se você está usando este repositório, considere deixar uma ⭐! Isso ajuda muito, obrigado :)_

---

### Servidores de exemplo

- teyvat: `748720691645251716` — [discord.gg/gibrasil](https://discord.gg/gibrasil)
- opera: `996403908530405406` — [discord.gg/operaepiclese](https://discord.gg/operaepiclese)
