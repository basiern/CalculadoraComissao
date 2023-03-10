//Trata-se de pseudocódigo para calcular salário bruto e comissão com base no valor de vendas por um funcionário. O pseudocódigo foi criado para ser rodado no portugol em virtude do aprendizado na cadeira de lógica da programação na graduação

programa
{
	
	funcao inicio()
	{
		real total, comissao, salariobruto

		escreva("Vamos calcular o seu salário bruto. \nQual o total vendido por você esse mês?")
		leia(total)

		comissao=total*0.1
		salariobruto = comissao + 1200

		escreva("Salário bruto é igual a: ",salariobruto, "\n", "Comissão é igual a ",comissao)
	}
}