# 📚 Catálogo e Padronização de Itens — Contatus Medware

## 🎯 Objetivo deste Repositório
Este repositório foi criado para mapear, organizar e padronizar toda a taxonomia de **Sistemas**, **Módulos** e **Submódulos** utilizada no registro de atendimentos internos da Medware (sistema Contatus).

O objetivo principal é:
* **Padronizar a abertura de chamados:** evitar descrições divergentes para o mesmo tipo de atendimento.
* **Construção colaborativa:** permitir que toda a equipe técnica contribua adicionando novos submódulos, regras de negócio e particularidades que surgem no dia a dia do suporte.
* **Histórico centralizado:** manter um ponto único de consulta com controle de versão de todas as alterações.

---

## 📂 Sistemas Mapeados

Acesse os arquivos abaixo para consultar ou complementar a relação de módulos e submódulos de cada produto:

* [Medware Clínicas](sistemas/MedwareClinicas.md)
* [API de Integração](sistemas/API.md)
* [DICOM / PACS](sistemas/Dicom.md)
* [Laudos Flex](sistemas/LaudosFlex.md)
* [Laudos UX](sistemas/LaudosUX.md)
* [Medware App / Agenda](sistemas/MedwareApp.md)
* [Medware Image](sistemas/MedwareImage.md)
* [Portal Meus Exames](sistemas/MeusExames.md)
* [Paciente Conectado / Multichat](sistemas/PacienteConectado.md)

---

## 🛠️ Manual de Colaboração (Como Adicionar Informações)

Você não precisa de comandos de terminal ou Git instalado; todo o processo pode ser feito em poucos cliques pelo próprio navegador.

### Opção 1: Adicionar ou Editar Diretamente no Arquivo (Mais Rápido)

1. Entre na pasta correspondente e **clique no arquivo** do sistema desejado (ex: `sistemas/MedwareClinicas.md`).
2. No canto superior direito da tela do arquivo, clique no **ícone de lápis** (*"Edit this file"*).
3. Na tabela, vá até o final e adicione uma nova linha seguindo a estrutura padrão separada por barras retas (`|`):
   ```markdown
   | Módulo Principal | Nome do Submódulo | Descrição do caso / Exemplo |
