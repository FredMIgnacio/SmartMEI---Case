
**Utilizar lógica de programação**

**1 –** 


    funcao destravar(sistemaDeBloqueio) {
    	se (sistemaDeBloqueio == pin) {
    		se (pinDigitado == pinValido) {
    			retorna verdadeiro;
    		} retorna falso;
    	} ou (sistemaDeBloqueio == senha) {
    		se (senhaDigitada == senhaValida) {
    			retorna verdadeiro;
    		} retorna falso;
    	} ou (sistemaDeBloqueio == leitorDeDigital) {
    se (digitalProvidenciada == digitalValida) {
    			retorna verdadeira;
    		} retorna falso;
    	};
    };



    funcao abrirApp(mao, bolso, smartphone, app) {
    	coloca a mao no bolso;
    	pega o smartphone;
    	liga tela do smartphone;
    	se (destravar()) {
    		exibir apps;
    		se (apps possui app) {
    			selecionar app;
    		}
    	};
    };

	//exemplo
	abrirApp(mão esquerda, bolso esquerdo do casaco, Xiaomi MiA2, SmartMEI);

**2 –**


    funcao conversorDeTemperatura(F) {
    	variavel C = (F – 32)5/9;
    	escrever(“o valor de ” + F + “Fahrenheits em Célsius é ” + C);
    };

	//exemplo
	conversorDeTemperatura(212);
	// “o valor de 212 Fahrenheits em Célsius é 100”