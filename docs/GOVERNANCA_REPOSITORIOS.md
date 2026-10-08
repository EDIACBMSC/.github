# Governança dos repositórios EDIACBMSC

## Papel dos serviços Git

O GitLab institucional do CBMSC é a fonte oficial dos projetos corporativos. A organização GitHub `EDIACBMSC` é complementar e recebe conteúdo somente mediante autorização expressa.

GitHub e GitLab são destinos independentes. Não existe sincronização automática entre eles.

## Catálogo inicial

| Repositório | Visibilidade | Papel |
|---|---|---|
| `EDIACBMSC/.github` | Público | Perfil e padrões públicos da organização |
| `EDIACBMSC/SAINA` | Privado | Código, SQL, testes e documentação técnica do SAINA |

Novos repositórios devem ser criados somente quando o conteúdo não couber adequadamente nos repositórios existentes.

## Regras

1. Cada repositório deve declarar finalidade, responsável e visibilidade.
2. Projetos operacionais são privados por padrão.
3. Conteúdo público exige classificação, sanitização e revisão.
4. Credenciais e dados operacionais brutos não pertencem ao Git.
5. Escrita no GitHub exige pedido explícito para o GitHub.
6. Qualquer ação no GitLab exige autorização independente.
7. Editar, criar commit, fazer push, abrir Pull Request e mesclar são ações distintas.
8. O estado remoto deve ser relido depois de cada publicação.
9. Um remoto configurado não representa autorização para publicar.
10. Repositórios de terceiros ou de outro responsável são somente leitura até autorização específica.

## Fluxo de mudança

```text
estado remoto
    ↓
classificação do conteúdo
    ↓
branch curta
    ↓
alteração mínima
    ↓
testes e revisão de segredos
    ↓
commit convencional
    ↓
push autorizado
    ↓
Pull Request
    ↓
revisão e merge autorizado
    ↓
verificação remota
```

## Convenções

Branches:

- `feat/descricao`
- `fix/descricao`
- `docs/descricao`
- `test/descricao`
- `chore/descricao`

Commits seguem o padrão Conventional Commits, com escopo quando ele ajudar a identificar a área alterada.

## Verificação mínima

Antes da publicação:

- confirmar identidade autenticada;
- confirmar organização, repositório e visibilidade;
- confirmar branch atual e branch padrão;
- revisar diff e arquivos não rastreados;
- executar testes relevantes;
- verificar segredos e dados pessoais;
- confirmar que o GitHub é o destino autorizado.

Depois da publicação:

- reler Pull Request ou commit remoto;
- comparar o SHA local com o remoto;
- conferir a lista de arquivos alterados;
- registrar o que foi verificado e o que permanece assumido.
