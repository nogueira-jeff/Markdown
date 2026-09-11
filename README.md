# Markdown
Testing markdown 



**olá** - negrito !Dois asteriscos antes e dois depois 
__olá__ - negrito !Dois underlines antes e dois depois

*olá* - italico !Um asterisco antes e um depois
_olá_ - itálico !Um underline antes e um depois

_*olá*_ - negrito e italico !Um underline e um asterisco + palavra + um asterisco e um underline

~~olá~~ - riscado !Dois tils antes e dois depois

# titulo nivel 1 !Uma hashtag antes
## titulo nivel 2 !Duas hashtags antes
### titulo nivel 3 !Três hashtags antes

--- 
linha horizontal !Três traços 

*** 
linha horizontal !Três asteriscos também funciona

##Lista numerada

1. teste !1. + palavra 
1. teste 2 !A partir do segundo pode ser '2., 3., etc' ou continuar com 1."
1. teste 3
1. teste 4
   1. sub item teste 4 !Criar subitem: 3x espaço + 1. ...)
1. teste 5


##Lista demarcada

* teste !1 asterisco antes gera lista sem números
* teste
* teste
   * teste !Criar subitem nessa lista: 3x espaço + 1 asterisco
* teste   
!Também serve traço no lugar dos asteriscos



##Lista de tarefas: !Traço + 1 espaço + [] com espaço dentro  

- [x] Criar a página principal
- [x] Criar a página da loja
- [ ] Finalizar a reunião com o cliente
- [ ] Receber pagamento
!Para marcar com x, só tirar o espaço de dentro dos colchetes e colocar o x.

##Tabela: !nomeColuna + espaço + pipe + espaço + nomeColuna ..., abaixo três traços + pipe + três traços + pipe..., abaixo itens da tabela seguindo mesmo padrão do cabeçalho


Num | Nome | Nota
---|---|---
1 | Jefferson | 9,0
2 | José | 10,0 
3 | Maria | 7,5


##Exemplo de como identificar que tal parte é um comando:

Não sei para que serve o comando `document.getElementById()` na linguagem JavaScript. 
!Colocar o comando entre crases


##Trecho de programa:

``` 

num = int(input('Digite um valor: ')
if num % 2 == 0:
    print(f'O valor {num} é PAR')
else
    print(f'O valor {num} é ÍMPAR')

```

!Três crases + pula 1 linha + codigo + pula 1 linha + 3 crases