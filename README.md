# Automação de atualização de matrículas de beneficiários (plano de saúde)

## Problema
Ao cadastrar novos beneficiários em determinados produtos, o sistema gerava matrículas fora do padrão numérico esperado, exigindo intervenção manual do time de TI para correção diretamente no banco de dados.

## Solução
Desenvolvimento de uma interface web que permite ao usuário ajustar a matrícula do beneficiário de forma simples e controlada, eliminando a necessidade de consultas e updates manuais no banco.

A solução realiza:
- Recebimento de identificador do beneficiário
- Atualização do código de matrícula diretamente no banco
- Execução simplificada via interface para o usuário final

## Impacto
- Redução da dependência do time de TI para correções operacionais
- Maior autonomia para usuários de negócio
- Diminuição de retrabalho e tempo de atendimento
- Padronização dos dados de matrícula

## Tecnologias utilizadas
- Python
- Banco de dados Oracle
- Interface web (HTML/CSS)

## Observações
Evolução prevista para incluir validação e exibição dos dados antes da atualização, aumentando segurança e rastreabilidade.

## Autor
João Eduardo da Silva Teixeira
