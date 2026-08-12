Guia da linguagem Markdown
Simbolos e marcas
Principalmente usado no GitHub nos devidos locais:

Arquivo: "README.md" (ou qualquer arquivo (.md))
Nas Issues
Pull Requests

# Titulo
## Titulo
### Titulo         "Aplicar espaço após o #"
#### Titulo
##### Titulo

*** ou --- Serve para criar uma linha divisoria no texto.

**Negrito**
__Negrito__

*Italico*
_Italico_

__*É possivel misturar as configurações juntando as funções*__ (Negrito italico)

~~Risca Texto~~

# Lista Numerada
Adicione numero com ponto, e espaço, após, o nome do item, EX:
1. Teste
2. Teste 2
3. Teste 3

Também é possivel adicionar subitens dentro das listas numeradas.
Basta adicionar identação dentro da lista numerada desejada.
Ex:
1. Teste
2. Teste 2
   1. A
   2. B
3. Teste 3

# Lista Demarcada
Funcionad a mesma forma que a lista numerada, porem devemos usar: * ou - ao invés de numeros.
EX:
* Teste
* Teste 2
    * A
    * B
* Teste 3

# Lista de Tarefas
Usamos o modelo prefixo "- [ ] texto" para definir a tarefa, ao concluir a tarefa editamos o texto adicionando um X dentro do colchete: "- [X] texto" assim é apresentado um sinal de "correto" como tarefa concluida: 

- [X] Criar Página principal
- [ ] Criar Página de Vendas
- [ ] Reuniao com Fulano

# Imagens e arquivos
Abra seu explorador de arquivos, identifique a imagem desejada, e arraste para o texto em questão.(Nao é dificil identificar o local adequado para inserir a imagem)
EX:
<img width="234" height="238" alt="Image" src="https://github.com/user-attachments/assets/acbd648d-89bb-4d76-9357-3cdce3852c90" />

# Link em texto
Para adicionar Link dentro de texto, Use colchete e parenteses como no exemplo.
EX:
[Texto](URL DESEJADA)

[Acesse meu GitHub](https://github.com/Ericsystemsl)

# Criação de tabelas no Markdown
Num | Nome | Nota
---|---|---
1 | Gustavo | 8,5
2 | Jose | 10,0
3 | Maria | 9,0

Terminou a tabela

# Como adicionar Comandos
Para adicionar comandos dentro de um texto você deve adicionar "Crases"( acento para trás: ``) e o texto dentro.
Ex:
Não entendo direito para que serve o comando `document.getElementByld()` da linguagem JavaScript

# Para Mostrar trechos de programas
Coloca 3 crases para abrir e 3 para fechar. Ex:
E adiciona o trexo de programa no meio.
```
num = Int(Input('Digite o valor: '))
if num % 2 == 0:
    Print(f 'O Valor {num} é PAR')
Else
    Print(f'O Valor {num} é IMPAR') 

```

# Como adicionar Emoji
Para adicionar emoji simplesmente digite 2 pontos (:) e digite o nome do emoji desejado, ex:
🖖 (: vulcan_salute sem o espaço), basicamente o chat de comment ja te ad as opções

# Respondendo comentarios
Basta adicionar o sinal de maior (> texto a ser respondido)