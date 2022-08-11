# calsse-e-objetos

Enquanto	ainda	há	tentativas,	faça:
								chute_str	=	input('Digite	o	seu	número:	')
								print('Você	digitou:	',	chute_str)
								chute	=	int(chute_str)
								acertou	=	numero_secreto	==	chute
								maior	=	chute	>	numero_secreto
								menor	=	chute	<	numero_secreto
								if	(acertou):
												print('Você	acertou!')
								elif	(maior):
												print('Você	errou!	O	seu	chute	foi	maior	que	o	número	secreto')
								elif	(menor):
												print('Você	errou!	O	seu	chute	foi	menor	que	o	número	secreto')
								print('Fim	do	Jogo!')


class	Conta:
				#código	omitido
				def	deposita(self,	valor):
								self.saldo	+=	valor
								self.historico.transacoes.append("depósito	de	{}".format(valor))
				def	saca(self,	valor):
								if	(self.saldo	<	valor):
												return	False
								else:
												self.saldo	-=	valor
												self.historico.transacoes.append("saque	de	{}".format(valor))
				def	extrato(self):
								print("numero:	{}	\nsaldo:	{}".format(self.numero,	self.saldo))
								self.historico.transacoes.append("tirou	extrato	-	saldo	
								de	{}".format(self.saldo))
                
                
                
                
                
                
                
