# sanguebom-api

https://sanguebom-api.onrender.com. (no meu email pessoal)

https://sanguebom-api-ouyw.onrender.com (na conta com email compartilhado da dupla)


*Lembrar de alterar*

Priorizar a hierarquia das informações (por exemplo: em Doações > Hemocentro vem primeiro, depois Doador, Tipo Sanguineo e Quantidade Doada.  
**FEITO!**   

Confirmar os atributos que estão duplicados (por exemplo: email em Usuários e email em Doadores, Hemocentros e afins).  
**Removi os "email" duplicados e os "tipoS", mas não observei mais nada duplicado.**

Convocações, estoques, solicitações e doações: remover o preenchimento do "tipoS".  
**FEITO!**   

Doadores: alterar "Data de Nascimento" para tipo Data ao invés de String.  
**Não existe tipo data em json puro, deve ser feita uma conversão no código**

Hemocentros: adicionar endereço (separando campos), telefone, razão social, CNPJ.  
**FEITO!**

Adms: alterar "nome" para "Login".  
**FEITO!**

Instituições: remover campo "nome", adicionar endereço em capos separados).  
**FEITO!**

Solicitações: remover campo "qdtLiberada", "status".  
**FEITO!**

Doações: criar campo para data da doação (verificar como adicionar calendário no input).  
**FEITO!**

Criar nova coleção para registrar as solicitaççoes recebidas pelo hemocentro, onde será cadastrada a quantidade liberada, o status e talvez a data de liberação.  
**FEITO!**
