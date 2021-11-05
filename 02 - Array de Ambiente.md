Array no Shell: `testeArray=(item0 item1 item2)`

## Acessando Valores:

**Um elemento:** `echo ${testeArray[1]}`

**Todos os elementos:** `echo ${testeArray[*]}`


## Removendo ou Alterando Valores:
	
**Alterar um elemento:** `testeArray[2]=outroItem`

**Um elemento:** `unset testeArray[2]`

**Todos os elementos:** `unset testArray[*]`

## Adicionando um Novo Elemento:

`testeArray[3]=item3`


