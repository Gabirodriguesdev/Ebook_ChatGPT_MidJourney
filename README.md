# Ebook_ChatGPT_MidJourney
Criando um Ebook com ChatGPT &amp; MidJourney

PROMPTS :
Faça um texto para ebook, com foco em linguagem Lua com exemplos em código , para usar em programação no Roblox, nível iniciante. 

{REGRAS}

> EXPLIQUE SEMPRE DE UMA MANEIRA SIMPLES
> DEIXE O TEXTO ENXUTO
> SEMPRE TRAGA EMPREMPLOS DE CÓDIGOS EM CONTEXTOS REIAS
> SEMPRE DEIXE UM TÍTULO SUGESTUVO POR TÓPICO
>
> Ebook:
>
> **Ebook: Introdução à Linguagem Lua para Programação no Roblox - Nível Iniciante**

**Tópico 1: O Mundo da Programação no Roblox**
Vamos entrar no emocionante mundo da programação no Roblox! Neste ebook, você aprenderá a usar a linguagem Lua para criar seus próprios jogos e experiências incríveis no Roblox. Vamos começar!

**Tópico 2: Primeiros Passos**
Antes de mergulharmos nos códigos, vamos conhecer o ambiente de programação no Roblox. Você vai aprender a abrir o Studio, criar um novo jogo e entender as diferentes áreas da interface. Vamos lá!

**Tópico 3: Comandos Básicos**
Vamos começar com os comandos mais simples em Lua. Aqui estão alguns exemplos:

**Título: Mostrando uma Mensagem na Tela**
```lua
print("Olá, Roblox!")
```
Este código imprimirá "Olá, Roblox!" no console do Studio sempre que você executá-lo. Simples assim!

**Título: Variáveis e Números**
```lua
local minhaIdade = 12
local meuPeso = 45.5
```
Neste exemplo, criamos duas variáveis: `minhaIdade` e `meuPeso`. A primeira é uma variável do tipo inteiro (número inteiro) e a segunda é uma variável do tipo número decimal (número de ponto flutuante).

**Título: Operações Matemáticas**
```lua
local a = 5
local b = 3
local resultado = a + b
```
Neste código, realizamos a soma de duas variáveis e armazenamos o resultado na variável `resultado`.

**Tópico 4: Tomando Decisões**
Agora, vamos aprender a tomar decisões no nosso código usando estruturas condicionais:

**Título: Estrutura "if"**
```lua
local idade = 10
if idade < 13 then
    print("Você é um jogador iniciante!")
end
```
Neste exemplo, verificamos se a variável `idade` é menor que 13. Se for, mostramos a mensagem "Você é um jogador iniciante!".

**Título: Estrutura "if-else"**
```lua
local pontos = 100
if pontos >= 100 then
    print("Parabéns, você venceu o jogo!")
else
    print("Tente novamente para conseguir mais pontos!")
end
```
Neste código, avaliamos se a variável `pontos` é maior ou igual a 100. Se for, mostramos a mensagem de vitória; caso contrário, mostramos uma mensagem de incentivo.

**Tópico 5: Repetições**
Agora, vamos aprender a repetir ações usando loops:

**Título: Loop "while"**
```lua
local contador = 1
while contador <= 5 do
    print("Contagem: " .. contador)
    contador = contador + 1
end
```
Neste exemplo, o loop `while` irá imprimir a contagem de 1 a 5.

**Título: Loop "for"**
```lua
for i = 1, 5 do
    print("Contagem: " .. i)
end
```
Neste código, o loop `for` também imprimirá a contagem de 1 a 5.

**Tópico 6: Funções**
Vamos aprender a criar nossas próprias funções para reutilizar código:

**Título: Criando uma Função**
```lua
local function saudacao(nome)
    print("Olá, " .. nome .. "!")
end

saudacao("Lucas")
saudacao("Bia")
```
Neste exemplo, criamos a função `saudacao`, que recebe um nome como parâmetro e imprime uma mensagem de saudação com o nome fornecido.

**Tópico 7: Eventos**
Por fim, vamos entender como lidar com eventos no Roblox:

**Título: Detectando Cliques**
```lua
local botao = script.Parent
local function aoClicar()
    print("Você clicou no botão!")
end

botao.MouseButton1Click:Connect(aoClicar)
```
Neste código, criamos uma função `aoClicar` que será executada sempre que o botão for clicado.

**Conclusão**
Parabéns! Agora você tem uma base sólida para começar a criar seus próprios jogos no Roblox usando a linguagem Lua. Continue praticando, explorando e se divertindo enquanto desenvolve suas habilidades como programador. Lembre-se sempre de se desafiar, aprender com os erros e nunca parar de criar! O céu é o limite!
