# Política de segurança

## Escopo

Esta política se aplica aos repositórios da organização GitHub `EDIACBMSC`.

## Comunicação de vulnerabilidade ou exposição

Não abra issue pública para relatar vulnerabilidade, credencial exposta, dado pessoal ou informação institucional restrita.

Use o canal institucional interno definido para o projeto. Quando o canal não estiver documentado, procure o responsável institucional pelo repositório antes de compartilhar detalhes.

## Resposta inicial

Em caso de suspeita de exposição:

1. interrompa novas publicações relacionadas;
2. preserve somente a evidência necessária para análise;
3. revogue ou rotacione a credencial exposta;
4. não repita o segredo em issue, commit corretivo ou documentação;
5. avalie o alcance nos clones, logs, artefatos e histórico remoto;
6. registre a correção pelo canal institucional apropriado.

Não reescreva histórico, apague evidência ou altere ambientes sem decisão técnica e autorização específicas.

## Dados pessoais

Não publique dados pessoais para demonstrar um defeito. Use exemplos fictícios ou sanitizados que preservem apenas a estrutura necessária para reproduzir o problema.

## Segredos

Tokens, senhas, chaves, cookies, `.env`, kubeconfigs e URLs com credenciais são proibidos em qualquer arquivo versionado.
