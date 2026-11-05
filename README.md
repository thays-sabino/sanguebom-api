# sanguebom-api

https://sanguebom-api.onrender.com. (no meu email pessoal)

https://sanguebom-api-ouyw.onrender.com (na conta com email compartilhado da dupla)


*Lembrar de alterar*

Priorizar a hierarquia das informações (por exemplo: em Doações > Hemocentro vem primeiro, depois Doador, Tipo Sanguineo e Quantidade Doada.  
Confirmar os atributos que estão duplicados (por exemplo: email em Usuários e email em Doadores, Hemocentros e afins).  
Convocações, estoques, solicitações e doações: remover o preenchimento do "tipoS".  

Doadores: alterar "Data de Nascimento" para tipo Data ao invés de String.  
Hemocentros: adicionar endereço (separando campos), telefone, razão social, CNPJ.  
Adms: alterar "nome" para "Login".  
Instituições: remover campo "nome", adicionar endereço 9em capos separados).  
Solicitações: remover campo "qdtLiberada", "status".  
Doações: criar campo para data da doação (verificar como adicionar calendário no input). 


Criar nova coleção para registrar as solicitaççoes recebidas pelo hemocentro, onde será cadastrada a quantidade liberada, o status e talvez a data de liberação.
