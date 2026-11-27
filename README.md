# Sistema de Notas de Alunos

## Sobre o projeto

Sistema de linha de comando em **C** para gerenciar notas de alunos, desenvolvido como Projeto Final da disciplina de Lógica de Programação (UCB, Engenharia de Software).

Os dados ficam em um arquivo texto (`alunos.txt`), com um registro por linha e campos separados por `;`. Ao iniciar, o programa carrega os registros na memória; se o arquivo não existir, avisa e começa vazio. Os dados são salvos após cada alteração e ao sair.

Registro de cada aluno: `codigo;nome;disciplina;nota`

```
101;Ana Souza;Logica de Programacao;8.50
```

## Funcionalidades

| Opção | Operação | Descrição |
|:-----:|----------|-----------|
| 1 | Cadastrar | Cadastra um novo aluno (código, nome, disciplina e nota) |
| 2 | Listar | Exibe todos os registros em tabela alinhada |
| 3 | Buscar | Busca por código ou por nome |
| 4 | Alterar | Edita os dados de um registro existente |
| 5 | Excluir | Remove um registro após confirmação `Tem certeza? S/N` |
| 6 | Gerar relatório | Gera `relatorio.txt` e exibe o mesmo conteúdo na tela, com total de registros, média, maior e menor nota |
| 7 | Sair | Salva os dados e encerra o programa |

## Autores
| Matheus Vieira Rocha
