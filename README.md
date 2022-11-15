[![almatos's 42 Libft Score](https://badge42.vercel.app/api/v2/cla88p9vf00110fmd8v1byjg9/project/2849382)](https://github.com/JaeSeoKim/badge42)
## Parte 1 - Funções Libc "MANDATORY PART"

### Funções da biblioteca `<ctype.h>`
- [x] Função `ft_isalpha` - Teste de caracteres alfabéticos. 
- [x] Função `ft_isdigit` - Teste de caractere de dígito decimal. 
- [x] Função `ft_isalnum` - Teste de caracteres alfanuméricos. 
- [x] Função `ft_isascii` - Teste para caracteres ASCII. 
- [x] Função `ft_isprint` - Teste de caracteres de impressão (incluindo caracteres de espaço). 
- [x] Função `ft_tolower` - Conversão de letras maiúsculas para minúsculas. 
- [x] Função `ft_toupper` - Conversão de letras minúsculas para maiúsculas. 

### Funções da biblioteca `<stdlib.h>`
- [x] Função `ft_atoi` - Converter string ASCII para inteiro. 
- [x] Função `ft_calloc` - Reserva memoria de acordo com o tamanho e o tipo desejado e preeche com nulls.

### Funções da biblioteca `<strings.h>`
- [x] Função `ft_bzero` - Escreve zeros em uma string de bytes. 
- [x] Função `ft_memset` - Escreve um byte em uma string de bytes. 
- [x] Função `ft_memcpy` - Copiar blocos de memória do source para o destino. 
- [x] Função `ft_memmove`- Copiar cadeia de bytes. 
- [x] Função `ft_memchr` - Localizar um caracter num bloco de memória.
- [x] Função `ft_memcmp`- Comparar blocos de memória entre s1 e s2. 

### Funções da biblioteca `<string.h>`
- [x] Função `ft_strlen` - Retorna o tamanho de uma string. 
- [x] Função `ft_strlcpy` - Copiar strings. 
- [x] Função `ft_strlcat` - Concatenação de strings limitadas por tamanho. 
- [x] Função `ft_strnstr` - Localizar uma substring em uma string (limitada por tamanho).
- [x] Função `ft_strchr` - localizar a primeira ocorrencia do caractere na string.
- [x] Função `ft_strrchr` - localizar a última ocorrência  do caractere na string.
- [x] Função `ft_strncmp` - Compara strings limitadas por tamanho.
- [x] Função `ft_strdup` - Copia uma string para a memoria.

## Parte 2 - Adicionais funções "MANDATORY PART"
- [x] Função `ft_substr` - Cria uma string a partir de uma maior, iniciando no byte 'start' com tamano de n bytes 'len'.
- [x] Função `ft_strjoin` - Aloca e retorna uma nova string, que é o resultado da concatenação de 's1' e 's2'.
- [x] Função `ft_strtrim` - Aloca com o malloc e retorna uma copia de 's1' com os caracteres especificados em 'set' removidos no inicio e no fim da string.
- [x] Função `ft_itoa` -  Converte inteiro em uma string de char, alocando antes a memoria com malloc.
- [x] Função `ft_putchar_fd` - Gera um char 'c' de acordo com a descrição 'fd' ex: fd = 0(input); fd = 1(output).
- [x] Função `ft_putstr_fd` - Gera uma string 's' de acordo com a descrição 'fd' ex: fd = 0(input); fd = 1(output).
- [x] Função `ft_putendl_fd` - Gera uma string 's' seguida por quebra de linha de acordo a descrição'fd' ex: fd = 0(input); fd = 1(output).
- [x] Função `ft_putnbr_fd` - Gera o inteiro 'n' de acordo com a descrição 'fd'.
- [x] Função `ft_split` - Retorna um array de strings obitidas na divisao de 's' usando separador 'c'. A matriz de ve terminar com um ponteiro NULL.
- [x] Função `ft_striteri` - Aplica a função 'f' a cada caractere do string 's', e passando seu índice como primeiro argumento
para criar uma nova string com malloc resultando de aplicações sucessivas de 'f'.
- [x] Função `ft_strmapi` -  Aplica a função 'f' em cada caractere da string 's', passando seu índice como primeiro argumento. Cada caractere é passado por
endereço (&s[index]) para 'f' para ser modificado se necessário.

## "BONUS PART"
- [x] Função `ft_lstnew` - Cria um novo 'node' e reserva memória(malloc), a variavel 'content' aponta para o conteudo do parametro '*content' , a variavel 'next' aponta para 'NULL'.
- [x] Função `ft_lstadd_front` - Adiciona o 'node' no inicio e aponta o 'next' para o inicio do proximo 'node', salvando a posicao atual '*list = new'.
- [x] Função `ft_lstsize` - Conta o número de nós em uma lista e retorna um inteiro.
- [x] Função `ft_lstlast` - Retorna o ultimo 'node' da lista.
- [x] Função `ft_lstadd_back` - Adiciona um novo 'node' no final da lista.
- [x] Função `ft_lstdelone` -  Exclui todo conteudo no content do '*lst'(node dado como parâmetro), usando a função 'del'(função dada como parâmetro) em siguida libertando a memoria do 'lst'(node parâmetro).
- [x] Função `ft_lstclear` - Exclui '*lst'(node dado como parâmetro ) e os próximos node's até chegar ao fim da lista liberando toda a memoria de cada 'node'(free), usando a funcao  'dell'(dada como parâmetro), o ponteiro para a lista deve ser definido como 'nulo'.
- [x] Função `ft_lstiter` - Itera a lista 'lst' e aplica a função 'f' no content de cada 'node' até o fim da lista.  

## Falta fazer - "BONUS PART"
- [ ] Função `ft_lstmap` -
