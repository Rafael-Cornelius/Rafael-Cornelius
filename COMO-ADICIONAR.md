# Como adicionar um trabalho

[Voltar aos estudos](FACULDADE.md)

## 1. Escolha onde colocar

| O que você fez | Onde adicionar |
|---|---|
| Exercício básico de Portugol | [Portugol / basicos](https://github.com/Rafael-Cornelius/exercicios-portugol/tree/main/basicos) |
| Exercício de vetores em Portugol | [Portugol / vetores](https://github.com/Rafael-Cornelius/exercicios-portugol/tree/main/vetores) |
| Exercício com for em C | [C / for](https://github.com/Rafael-Cornelius/Exerc-cios-de-Repeti-o/tree/main/for) |
| Exercício com while ou do-while em C | [Repetição em C](https://github.com/Rafael-Cornelius/Exerc-cios-de-Repeti-o), na pasta do laço usado |
| Mais um exercício da segunda lista de C | [Segunda lista / exercicios](https://github.com/Rafael-Cornelius/Exercicios-em-C-segunda-lista/tree/main/exercicios) |
| Uma nova lista de C | Crie `lista-03/` no repositório de repetição em C; depois `lista-04/`, e assim por diante |
| Evolução de um circuito existente | Pasta `circuitos/` do projeto correspondente no [índice](FACULDADE.md) |
| Projeto independente ou outra disciplina | Crie um repositório próprio seguindo o passo 4 |

## 2. Dê um nome simples

Use **minúsculas, sem acentos, com hífens** nos nomes de arquivos, pastas e novos repositórios.
Nos títulos e explicações, escreva português normalmente.

| Evite | Use |
|---|---|
| `Untitled1.cpp` | `05-tabuada.cpp` |
| `trabalho final novo.zip` | Uma pasta com os arquivos do projeto |
| `teste2.por` | `06-inverter-vetor.por` |
| `Circuito FINAL.circ` | `contador-binario.circ` |

Use o próximo número livre da pasta. Mantenha a extensão do seu ambiente (`.c`, `.cpp`, `.por`, `.circ`).
Ao corrigir um exercício, atualize o mesmo arquivo: o histórico do Git guarda as versões.

## 3. Envie pelo site do GitHub

1. Abra o repositório e entre na pasta correta.
2. Selecione **Add file → Upload files** e arraste os arquivos de código.
3. Escreva uma mensagem curta, como `Adiciona exercício de tabuada`.
4. Selecione **Commit changes** para salvar.
5. Abra o `README.md` do repositório, clique no lápis e acrescente o link do exercício na lista.

Para criar uma pasta pelo site, use **Add file → Create new file** e digite o caminho completo,
por exemplo `lista-03/README.md`. Escreva o assunto da lista e salve; depois envie os códigos para essa pasta.

Envie os códigos editáveis. Arquivos `.exe`, `.o`, dependências instaladas e páginas inteiras do compilador
não são necessários para ler o trabalho. Se houver um enunciado, coloque-o em `docs/`.
O `.gitignore` ajuda no envio com Git, mas não impede uploads manuais pelo site.

## 4. Comece um projeto independente

1. No GitHub, escolha **New repository**.
2. Use um nome que explique o conteúdo, como `banco-de-dados-sql` ou `sistema-biblioteca`.
3. Escolha a visibilidade e marque a criação de um `README.md`.
4. Copie o [modelo de apresentação](modelos/README-PROJETO.md) para esse README e preencha os campos.
5. Adicione os arquivos. Crie somente as pastas que realmente precisar.
6. Acrescente uma linha no [índice da faculdade](FACULDADE.md) com o nome e o link.

| Local | O que guardar |
|---|---|
| `README.md` | Objetivo, tecnologia e como executar |
| `src/` | Código de uma aplicação com vários arquivos |
| `exercicios/` | Programas pequenos e independentes |
| `circuitos/` | Arquivos do Logisim |
| `docs/` | Enunciado, imagens e anotações, se houver |

Para um exercício isolado, basta o código na pasta do assunto. Não precisa criar uma aplicação inteira.

## Se usar Git no computador

Dentro da pasta do repositório, com suas alterações locais já salvas em commits:

```bash
git pull --ff-only
# Copie ou edite os arquivos na pasta correta.
git status
git add caminho/do/arquivo
git commit -m "Adiciona exercício de tabuada"
git push
```

Substitua `caminho/do/arquivo` pelo arquivo real; adicione também o README se o atualizar.
Se o `pull` indicar conflito ou divergência, resolva isso antes de continuar.

**Rotina:** escolher a pasta → nomear → enviar o código → atualizar o README.
