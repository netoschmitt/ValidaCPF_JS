### validação de CPF utilizando classes em JS

criada uma classe ValidaCPF, o construtor recebe 'cpfEnviado', utilizando metodo Object.defineProperty(), protegendo a prop..  e expressão regular removendo letras e caracteres- cpfEnviado.replace(/\D+/g, '').

criado metodo valida(), checando cpfLimpo, check typeof, e length do cpf 

metodo sequencia() checa se é uma sequencia válida, 

método geraNovoCPF() criando os digitos com a class ValidaCPF e método geraDigito

metodo static geraDigito(), gera a const digito, atravez da subtração de 11 e o resto da divisão entre o total e 11 e 
verifica se o digito for <= '9' return o digito, caso contrário return '0'; 




