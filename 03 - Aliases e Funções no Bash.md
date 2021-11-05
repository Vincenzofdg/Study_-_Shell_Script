## Aliases

Para mostrar os aliases criado digite no terminal `alias` apenas.

1. `alias mo='more'`
2. `alias lshome='cd /home; ls'`
3. **Para excluir um aliase:** `unalias comandoCriado`

## Funções

Parecido com o aliases, mas utiliza-se de um pequeno programa e nao de um comando.

**Exemplo:**

```
palavra() {
	cd /home/usuario
	echo 'Linha acrescentada' >> test_func
}
```

execulte `typeset -f | less` para ver as funções criadas no bash.