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