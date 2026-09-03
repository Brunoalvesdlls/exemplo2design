# SINTAXE MARKDOWN

## Título

```
# título principal
## Título da seção
### Título da sub seção
```

# título principal
## Título da seção
### Título da sub seção

## Formatação de texto
```
**texto em negrito**
*Texto em italico*
~~texto tachado~~
```
**texto em negrito**

*Texto em italico*

~~texto tachado~~


## lista
- primeiro item  
- segundo item
    - subitem identado
    - outro subitem
  
1. primeiro passo
2. segundo passo
3. terceiro passo
   
## checklist

```
- [x] tarefa concluida
- [ ] tarefa pendente
```
- [x] tarefa concluida
- [ ] tarefa pendente
  
  ## links
  [Visite o Github](https://github.com/)

  [Simpre badges](https://badges.pages.dev/)

  [abra outro arquivo do projeto](./outro.md)

  ## codigo em linha e blocos de codigos

  use uma crase para destacar um comando ou trecho curto no meio de uma frase.

  O comando `git status` mostra o estado atual do repositorio.

  o comando `git add.` adiciona os arquivos modificados à *staging area*. 


  O comando `git commit -m "Texto com a descrição do que foi feito"` Registra as alterações com uma mensagem. usar aspas sempre depois do comando e adicione um comentario

  O comando `git push origin main` sobe as alteraçoes para a nuvem.

```
git status
git add
git commit -m "texto com a descrição do que foi implementado"
git push origin main
``` 
## citaçoes

> uma boa documentação explica o objetivo, o uso e as limitações de um projeto.

## tabelas

| Tecnologia |finalidade|
| --- | ---|
|git | controle de versionamento|
Git Hub| hospedagem e colaboração|
|markdown| Documentação|

```
| Alinhamento à esquerda | Alinhamento ao centro |    Alinhamento à direita |
| :--- | :---: | ---: |
| Texto | Texto | Texto |
```
| Alinhamento à esquerda | Alinhamento ao centro |    Alinhamento à direita |
| :--- | :---: | ---: |
| Texto | Texto | Texto |


## imagens 
![42 Badge](https://img.shields.io/badge/42-000?logo=42&logoColor=fff&style=flat)

![.ENV Badge](https://img.shields.io/badge/.ENV-ECD53F?logo=dotenv&logoColor=000&style=flat-square)

![4chan Badge](https://img.shields.io/badge/4chan-060?logo=4chan&logoColor=fff&style=flat)

![homer simpson](./img/images.jpg)