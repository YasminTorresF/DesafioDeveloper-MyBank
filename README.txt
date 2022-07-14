My Bank App

Descrição: Aplicação de uma instituição financeira(Banco) 

Objetivo: 

Entidades: 
	- Client:
		- name
		- CPF
		- addressClient
		- phone
		- idAccont
		- idCard 

	- Agency:
		- idAgency
		- AddressAgency
	
	- Conta:
		- IdAccont
		- balance
		- statement
		
	- ATM:
		- idATM
		- addressATM

	- Card:
		- TipoCartão
		- idCard
		- idClient
		- idAccont
		- idAgency
		- passwordCard

	- transaction:
		- Transferência:
			- IdContaCliente
			- IdAgênciaCliente
			- IdContaDestino
			- IdAgênciaDestino
			- Valor
			- DataOperação
		- Saque:
			- IdContaCliente
			- IdAgênciaCliente
			- Valor
			- DataOperação
			- IdATM


Requisitos: 
- 
- 

Regras de negócio:
- 

Tecnologias utilizadas:
- Java

