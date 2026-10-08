# Como contribuir

## Antes de começar

1. Leia [a classificação da informação](docs/CLASSIFICACAO_INFORMACAO.md).
2. Leia [a governança dos repositórios](docs/GOVERNANCA_REPOSITORIOS.md).
3. Confirme que o GitHub é o destino autorizado para a mudança.
4. Confirme repositório, visibilidade, branch base e responsável pela revisão.

## Fluxo

1. Atualize o estado remoto.
2. Crie uma branch curta e descritiva.
3. Faça a menor alteração necessária.
4. Execute os testes relevantes.
5. Revise o diff e procure segredos e dados pessoais.
6. Crie um commit convencional.
7. Faça push somente com autorização explícita.
8. Abra um Pull Request.
9. Verifique os arquivos e o SHA no remoto.
10. Mescle somente após autorização e revisão compatíveis.

## Branches

- `feat/descricao`
- `fix/descricao`
- `docs/descricao`
- `test/descricao`
- `chore/descricao`

## Commits

Exemplos:

```text
feat(database): adicionar estrutura de persistência
fix(workflow): corrigir vínculo entre resposta e envio
docs: atualizar mapa do repositório
test: validar rollback da migration
chore: atualizar configuração do projeto
```

## Autorizações independentes

- Editar não autoriza commit.
- Commit não autoriza push.
- Push não autoriza Pull Request.
- Pull Request não autoriza merge.
- Autorização para GitHub não autoriza ação no GitLab.
- Autorização para um repositório não vale para outro.

## Conteúdo proibido

Não envie credenciais, tokens, chaves, arquivos `.env`, dados pessoais inadequados, dumps, logs de produção, URLs internas ou exportações operacionais não sanitizadas.
