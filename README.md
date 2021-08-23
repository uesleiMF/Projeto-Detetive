console.log("PROJETO DETETIVE")



console.log()
	
	console.log("O intuito deste programa e ajudar a solucionar crimes praticados no ambito da sociedade.Abaixo serao preenchidos alguns dados.")
	

	console.log()

		
	function pergunta(texto){
	  let resposta = String(prompt(texto))
	  
	  if ((resposta.toLowerCase()) == 'sim'){
	    return 1;
	  } else {
	    return 0;
	  }
	
	}
	
	let pergunta1 = pergunta("Telefonou para a vítima?")
	
	console.log()
	
	let pergunta2 = pergunta("Esteve no local do crime?")
	
	console.log()
	
	let pergunta3 = pergunta("Mora perto da vítima?")
	
	console.log()
	
	let pergunta4 = pergunta("Devia para a vítima?")
	
	console.log()
	
	let pergunta5 = pergunta ("Já trabalhou com a vítima?")
	
	console.log()
	
	let soma = pergunta1+pergunta2+pergunta3+pergunta4+pergunta5
	
	let condicoes =["Inocente","Suspeita","Cúmplice","Assassino"] 
	
	console.log()
		
	
	console.log(`Voce foi declarado ${condicoes[soma]}`)
