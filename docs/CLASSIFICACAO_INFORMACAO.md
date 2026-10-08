# Classificação da informação

Todo conteúdo deve ser classificado antes de ser criado, movido, publicado ou compartilhado nos repositórios da organização `EDIACBMSC`.

| Classe | Exemplos | GitHub | GitLab institucional | Regra |
|---|---|---|---|---|
| Institucional público | Perfil, documentação pública e exemplo sanitizado | Permitido após revisão | Permitido conforme política institucional | Revisar antes da publicação |
| Institucional interno | Código, automação, arquitetura e runbook | Somente com decisão explícita e em repositório privado | Destino oficial | Aplicar acesso mínimo |
| Projeto operacional | SAINA, integrações e banco de dados | Somente em repositório privado autorizado | Destino oficial | Não sincronizar automaticamente |
| Dado pessoal ou sensível | CPF, telefone, ocorrência e mensagens | Proibido | Somente em ambiente institucional controlado | Aplicar finalidade, acesso e retenção |
| Credencial | Token, senha, chave, cookie e `.env` | Proibido | Proibido em arquivo versionado | Usar mecanismo de segredo aprovado |
| Terceiro | Biblioteca, template e código externo | Conforme licença | Conforme licença | Preservar autoria e licença |
| Rascunho pessoal | Experimento ou configuração individual | Repositório pessoal ou branch temporária | Área autorizada | Exige adoção antes de virar institucional |

## Regra de bloqueio

Quando a classificação estiver indefinida, interromper a escrita e consultar o responsável pelo conteúdo.

## Publicação pública

Antes de publicar, confirmar:

- ausência de credenciais e identificadores internos;
- ausência de dados pessoais ou institucionais restritos;
- remoção de URLs e arquitetura internas;
- licença e autoria de conteúdo de terceiros;
- autorização expressa para uso do GitHub;
- revisão do conteúdo final no remoto.

## Responsabilidade

A pessoa que propõe a publicação deve informar finalidade, público, classificação e destino. A aprovação de um conteúdo não autoriza automaticamente outras publicações ou repositórios.
