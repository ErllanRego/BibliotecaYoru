# Linux fundamentals part 2

Erllan Rego, 14 de Novembro de 2022

## Sobre SSH

Protocolo usado para acessar máquinas linux remotamente

> **SSH == Secure Shell**
> 

### **Sintaxe de conexão ssh:**

```bash
ssh login@ip_da_maquina
```

Logo após será solicitado a senha.

## COMANDOS RELACIONADOS A ARQUIVOS E DIRETÓRIOS:

## **touch**

Cria um arquivo em branco

Exemplo:

```bash
 touch nome_do_arquivo
```

## **mkdir**

Cria um diretório(pasta == diretório)

Exemplo: 

```bash
mkdir nome_da_pasta
```

## **rm**

Remove arquivos e diretórios

Exemplo(deletar arquivo): 

```bash
rm nome_do_arquivo
```

Exemplo 2(deletar diretório, necessário flag de recursividade): 

```bash
rm -R nome_do_diretório
```

## **cp**

Copia arquivos e diretórios

Exemplo: 

```bash
cp o_que_sera_copiado.txt nome_da_copia.txt
```

## **file**

Mostra o formato do arquivo

Exemplo: 

```bash
file nome_do_arquivo
```

## DIRETÓRIOS IMPORTANTES:

**etc/**→ Guarda arquivos usados pelo sistema operacional, senha dos usuários e etc.

**var/**→diretório usado pelas aplicações e serviços para guardar arquivos.

**root**/→ funciona como a “home” para o usuário root.

**tmp**/→ salva arquivos de forma temporária(funciona igual a uma memória ram). Útil para pentest já que por padrão qualquer um pode escrever arquivos nela.