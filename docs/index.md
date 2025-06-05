<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Sistema Falcão Sombrio para Drones&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Amanda Oliveira Pires Conde
* João Rocha Murgel
* Lucas Akio Funada Tsukamoto
* Eric Ken Kawabe


# Descrição do Projeto

*&lt;O projeto está relacionado com os desafios do desenvolvimento de drones bélicos da empresa "Securus Dynamics", cujo principal produto se chama de Aquila-x, com necessidade de implementação de sistemas operacionais (tempo real, segurança e
concorrência) e de banco de dados (armazenamento distribuído,
replicação e logs de auditoria).&gt;*

# Análise de Requisitos Funcionais e Não-Funcionais

<img width="562" alt="Captura de Tela 2025-04-09 às 17 59 42" src="https://github.com/user-attachments/assets/cd000fe7-6353-4b80-ace2-6cbc005eee96" />

<img width="532" alt="Captura de Tela 2025-04-09 às 18 00 18" src="https://github.com/user-attachments/assets/7569ee6b-21b5-4756-bc44-15ef22c18551" />


# Diagrama de Atividades

<img width="979" alt="Captura de Tela 2025-04-09 às 17 55 04" src="https://github.com/user-attachments/assets/973252ec-5f3c-4f5d-98f3-08fe24ec2bc9" />


# Diagrama de Casos de Uso

<img width="907" alt="Captura de Tela 2025-04-09 às 17 32 47" src="https://github.com/user-attachments/assets/16a64bff-aedb-45ed-8893-8f62fa27f87a" />


# Descrição dos Casos de Uso

O Operador Militar usa o sistema para controlar drones remotamente, monitorar telemetria e atribuir missões. O sistema gerencia a frota de drones, garantindo segurança nas comunicações e processamento de dados.

Ator Primário:
	•	Operador Militar

Atores Secundários:
	•	Sistema de Comunicação
	•	Banco de Dados
	•	Administrador
	•	Sistema Operacional
	•	IA do Drone

Pré-condições:
	•	O operador deve estar autenticado no sistema.
	•	A conexão segura com os drones deve estar estabelecida.

Fluxo Principal:
	1.	O operador solicita o controle de um drone remoto.
	2.	O sistema estabelece uma conexão segura e apresenta informações de telemetria em tempo real.
	3.	O operador gerencia a frota de drones, podendo atribuir missões específicas.
	4.	O banco de dados armazena missões e eventos, replicando os dados em tempo real.
	5.	O sistema operacional monitora os processos e prioriza tarefas críticas.
	6.	A IA do drone realiza sensoriamento do ambiente e navegação autônoma, caso necessário.
	7.	O operador confirma as ações executadas e finaliza o processo.

Fluxo Alternativo (4): Drone em Espera

a. Se não houver drones disponíveis para uma missão, o sistema informa o operador e sugere colocá-lo em uma lista de espera.
b. Se o operador aceitar, o sistema o notifica quando um drone estiver disponível e retoma a missão.
c. Se o operador não aceitar, ele pode modificar a missão ou encerrar o processo.

Fluxo de Exceção (4): Falha na Conexão Segura
	•	Se a conexão segura falhar, o sistema ativa um mecanismo de fallback para restabelecer a comunicação.
	•	Se a reconexão falhar, o sistema notifica o operador e desativa o controle remoto do drone.

Pós-condições:
	•	O drone executou a missão com sucesso ou foi colocado em modo de espera.
	•	Os dados da missão foram armazenados no banco de dados.

# Diagrama de Sequência

<img width="572" alt="Captura de Tela 2025-06-04 às 22 00 41" src="https://github.com/user-attachments/assets/6125a02a-9f2b-44de-bdc7-8771e404e450" />


# Diagrama de Classes

<img width="731" alt="Captura de Tela 2025-06-04 às 22 04 50" src="https://github.com/user-attachments/assets/2f25b57e-5efa-4379-9c10-e02b755fc78e" />

# Diagrama de Estados

![WhatsApp Image 2025-06-04 at 18 28 01](https://github.com/user-attachments/assets/689e007b-237a-4569-beaf-04b3e8c3c7c9)


# Diagrama de Implantação

<img width="482" alt="Captura de Tela 2025-06-04 às 22 06 37" src="https://github.com/user-attachments/assets/2003191c-8a8a-4bd2-8318-7d96f9bc643c" />


# Referências

Conteúdo e Material disponibilizados em aula.
