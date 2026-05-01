# Automação de atualização de matrículas de beneficiários (plano de saúde)

Solução desenvolvida para automatizar a correção de inconsistências cadastrais em matrículas de beneficiários, reduzindo dependência operacional do time de TI.

## Problema
Ao cadastrar novos beneficiários em determinados produtos, o sistema gerava matrículas fora do padrão numérico esperado, exigindo intervenção manual para correção diretamente no banco de dados.

## Solução
Desenvolvimento de uma interface web que permite ao usuário ajustar a matrícula do beneficiário de forma simples e controlada, eliminando a necessidade de consultas e updates manuais.

Fluxo da solução:
- Recebimento do identificador do beneficiário
- Atualização direta da matrícula no banco de dados
- Execução simplificada via interface para o usuário final

## Impacto
- Redução da dependência do time de TI para correções operacionais
- Maior autonomia para usuários de negócio
- Diminuição de retrabalho e tempo de atendimento
- Padronização dos dados de matrícula

## Tecnologias utilizadas
- Python
- Oracle
- HTML / CSS

## Observações
Evolução prevista para incluir validação e visualização dos dados antes da atualização, aumentando segurança e rastreabilidade.

## Autor
João Eduardo da Silva Teixeira
