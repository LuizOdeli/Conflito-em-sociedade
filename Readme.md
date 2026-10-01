# Caso Fictício: Conflito em Sociedade em Conta de Participação (SCP) Imobiliária

**Autor:** Luiz Felipe Odeli
**Instituição:** Católica SC (Campus Joinville)
**Disciplina:** Inteligência Artificial Jurídica
**Atividade:** Preparatória para a N1 (Aula 04)

## Finalidade do Projeto
Este repositório contém a construção de um fluxo técnico verificável de Inteligência Artificial aplicado a um caso jurídico fictício. O objetivo é demonstrar a aplicação segura de IA generativa no Direito por meio de RAG (Retrieval-Augmented Generation) manual, aplicação de regras de sanitização de dados, verificação de fontes e auditoria de respostas.

## Público-alvo
O projeto foi desenvolvido para avaliação acadêmica pelo Prof. Edson Vaz Lopes e serve como modelo para operadores do Direito que desejam compreender a estruturação de prompts seguros e o registro de auditoria de sistemas de IA.

## Limites
A IA está estritamente limitada a basear suas respostas apenas nos documentos doutrinários e legais fornecidos na pasta `apoio/` (`fonte_1.md` e `fonte_2.md`). O caso é inteiramente fictício. Não há uso de dados reais, documentos reais de clientes, processos reais ou informações protegidas por sigilo (todos os dados inventados passaram por sanitização). É terminantemente proibida a invenção de leis ou jurisprudências (alucinação) por parte do modelo.

## Critérios de Aceitação
O fluxo será considerado bem-sucedido se:
1. A resposta inicial da IA for embasada exclusivamente nas fontes fornecidas, citando expressamente os arquivos e trechos de origem.
2. Nenhuma informação pessoal ou sensível não tratada vazar para o modelo (anonimização e limites de sigilo comprovados).
3. As afirmações geradas pela máquina passarem por conferência humana estruturada.
4. Uma auditoria simular a detecção de alucinações ou promessas indevidas, permitindo uma revisão humana para a orientação inicial final.

## Instruções para Compreensão do Repositório (Protocolo e Registro)
Para que qualquer pessoa consiga compreender o trabalho, o repositório está organizado em pastas que refletem as etapas de um protocolo de uso seguro da IA em escritórios:
* **`entrada/`**: Contém o relato original e bruto do cliente, simulando o caso antes de qualquer filtro de confidencialidade.
* **`docs/`**: Documenta o "contrato" da tarefa (especificação) e os parâmetros rigorosos de sigilo que devem ser aplicados antes do uso da IA.
* **`apoio/`**: Guarda a versão já sanitizada (limpa de dados) e os textos legais (fontes) que servirão de base limitadora obrigatória para o RAG.
* **`prompts/`**: Registra os comandos (instruções) exatos criados para enviar ao modelo de linguagem, tanto para a consulta quanto para a auditoria.
* **`evidencias/`**: Funciona como o registro de todo o comportamento da máquina (respostas brutas) e a conferência humana detalhada (o que foi mantido, corrigido ou excluído).
* **`entrega/`**: O produto final, revisado por um operador humano, com limites e fontes devidamente identificados.

## Repositório
**URL Pública:** [text](https://github.com/LuizOdeli/Conflito-em-sociedade)