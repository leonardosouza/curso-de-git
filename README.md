## ![Dog](https://pipz.com/static/images/blog/eddie.png) Meu Curso de GIT ![Dog](https://pipz.com/static/images/blog/eddie.png)

### Inicializando um Projeto Rapidamente

1 - Crie um novo repositório no github **(público ou privado)**.

2 - Crie uma pasta vazia **(com o nome do projeto)**.

3 - Dentro desta pasta crie um arquivo utilizando o seguinte:

```bash
echo "# Meu Curso de GIT" >> README.md
```

4 - Inicialize o repositório:

```bash
git init
```

5 - Aceito as mudanças no arquivo README.md, utilizando:

```bash
git add README.md
```

6 - Faço a gravação **(commit)** das mudanças, utilizando:

```bash
git commit -m "iniciando o projeto"
```

7 - Crie a branch principal, utilizando:

```bash
git branch -M main
```

8 - Adicione a origem do repositório remoto **(github)**:

```bash
git remote add origin https://github.com/leonardosouza/curso-de-git.git
```

9 - Por fim, sincronize o branch remoto **(origin)** com as informações do branch local **(main)**:

```bash
git push -u origin main
```

### [Link do Projeto](https://github.com/leonardosouza/curso-de-git)
