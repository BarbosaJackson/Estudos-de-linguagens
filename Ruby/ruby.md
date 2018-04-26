# Saída

print ->

puts  ->

# Métodos

## Length 
Este método retorna o tamanho de uma string.

```rb
puts "Jackson".length
```

o código acima exibirá o valor 7 que é a quantidade de caracateres da string "Jackson"

## Reverse
Este métdodo retorna uma string invertida.

```rb
puts "jack".reverse
```

O código acima exibirá a string "kcaj" que é o inverso da string "jack"

## Upcase
Este método retorna uma string com todas as letras maiusculas.

```rb
puts "jackson".upcase
```

O código acima exibirá a string "jackson" com todas as letras maiusculas, ou seja, exibirá "JACKSON".

## Downcase
Este método retorna uma string com todas as letras minusculas.

```rb
puts "JACKSON".downcase
```

O código acima exibirá a string "JACKSON" com todas as letras minusculas, ou seja, exibirá "jackson".

# Comentarios

## Comentário de uma linha
Para comentar basta utilizar o caracter '#' e o texto do comentário em seguida.

```rb
# isto é um comentario
```

## Comentário multi-linha
para comentar varias linhas aninhadas se faz necessário o uso dos operadores '=begin' e '=end', onde o '=begin' indica onde o comentário se inicia e o '=end' onde ele termina.

```rb
=begin
isto
é
um
comentário de várias linhas.
=end
```

