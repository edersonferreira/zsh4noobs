# Usando o Zsh

Usar o Zsh é como usar o Bash que você está acustumado, mas com alguns super-poderes, como o Tab melhorado que iremos ver, temas e plugins, mas na utilização de comandos é exatamente a mesma coisa, o que poderá mudar são algumas mensagens de erro do próprio shell, que poderão ser um pouco diferentes do Bash, mas não é algo que irá atrapalhar o seu uso.

Nós instalamos o Zsh, agora, para definir ele como shell padrão do nosso sistema, use este comando abaixo para definir o Zsh como shell padrão:

`chsh -s $(which zsh)`

A função deste comando é alterar o Shell padrão apenas para o seu usuário, não afetando outros usuários na máquina, assim, se você trocar de usuário e começar a usar o usuário root da máquina por exemplo, ele ainda estará com o bash, para fazer com que o root também esteja com o Zsh, será necessário executar este mesmo comando logado como root.

Se você quiser executar o zsh sem reiniciar o computador, digite:

`zsh`

O Zsh será iniciado no terminal que você está.

![Output 1](../../assets/usando-zsh/output-1.png)

## Proximo =>

[Tab, seu melhor amigo!](../tab/README.md)
