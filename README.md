# Media-Fundamental

# Algoritmo

inicio
	enquanto i ==1 faça
		exibir("Digite seu RA: ");
		ler ra;
		se ra dor diferente de 0 faça
			exibir("Digite a primeira nota: ");
			ler nota_um;

			exibir("Digite a segunda nota: ");
			ler nota_dois;

			exibir("Digite a terceira nota: ");
			ler nota_tres;
	
			result = (nota_um + nota_dois + nota_tres) / 3;

			se result >= 8 faça
				exibir("APROVADO!");
			fimse;

			senão se result >= 6 e < 8 faça
				exibir("RECUPERAÇÃO!");
			fimsenão;

			senão
				exibir("REPROVADO!");
			fimsenão;
		fimse;

		senão
			exibir("RA INVALIDO");
			i = 0;
		fimsenão;
fim



# Fluxograma

![Fluxograma media fundamental](https://user-images.githubusercontent.com/101130228/169937940-7ed86b89-6817-48cd-a53f-0afc36559e46.png)
