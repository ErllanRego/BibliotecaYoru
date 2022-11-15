# Linux fundamentals part 1

Erllan Rego, 13 de Novembro de 2022

## Comandos básicos de terminal(Ubuntu)

### **echo**

Imprime uma mensagem no terminal, aspas são opcionais.

Exemplo:

```bash
echo “Olá mundo”
```

Exemplo 2(sem aspas): 

```bash
echo Olá mundo
```

### **whoami**

Mostra qual usuário está sendo utilizado

Exemplo: 

```bash
whoami
```

### **ls**

Lista diretórios

Exemplo: 

```bash
ls
```

Exemplo 2(listar diretórios de uma pasta sem precisar estar nela): 

```bash
ls nome_do_diretório
```

### **cat**

Mostra conteúdo de arquivos de texto

Exemplo:

```bash
 cat exemplo.txt
```

### **cd**

Se move para diretórios

Exemplo: 

```bash
cd pasta_exemplo/
```

### **pwd**

Mostra diretório atual

Exemplo: 

```bash
pwd
```

### **find**

Achar diretório ou arquivo

Exemplo:

```bash
 find -name exemplo.txt
```

Exemplo 2(com base na extensão do arquivo): 

```bash
find -name *.txt
```

### **grep**

Achar entrada específica em um arquivo

Exemplo(entrada entre aspas e o nome do arquivo no final): 

```bash
grep “81.143.211.90” access.log
```

## Operadores

&→permite rodar comandos em segundo plano.

&&→permite combinar comandos para rodar mais de um por vez.

“>” → redirecionador, (echo palavra1 > texto.txt). Redireciona um echo para um arquivo de texto, porém sobrepõe o que tiver escrito lá.

“>>” → faz a mesma coisa do anterior porém não sobrepõe o que já tem escrito no arquivo(echo palavra2 >> texto.txt).