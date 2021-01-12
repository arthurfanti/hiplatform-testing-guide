# O que nos motivou a escrever isso?

Hoje nos falta confiança, enquanto desenvolvemos, de que podemos alterar determinada parte do software sem que isso acabe por gerar _bugs_ em alguma outra parte, seja por reuso de código, alto acoplamento ou outro motivo qualquer.
Isso se traduz em um desenvolvimento mais lento, processos de validação buroctáticos e igualmente lentos e, por fim, redução da velocidade com que poderíamos entregar novas _features_ que, consequentemente, aumentariam o valor percebido dos nossos produtos por parte dos clientes, usuários finais.

Quando falamos de testes, estamos falando essencialmente de **confiabilidade**. Confiança de que não estamos levando um _bug_ para produção enquanto subimos correção de outro. Confiança de que não vamos travar operação de algum cliente.

Mas, quando falamos de testes, também estamos falando de **manutenabilidade**. No fim das contas, um conjunto de testes unitários bem escritos pode servir, além de seu propósito mais óbvio, como documentação do código.