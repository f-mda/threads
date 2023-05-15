# Anotações threads
##Aula 01 - Introdução a threads
Em java, ao iniciar programa a JVM cria inicialmente a thread main.

Comandos de Thread vão utilizar a classe Thread

	Thread.sleep(tempo em milisegundos) 
	lança InterruptedException
	
No prompt de comando, executar

	jconsole
	
para abrir ferramenta que permite monitorar threads do Java.
Um diferencial da Máquina Virtual no início (1995) foi dar suporte nativo a threads.

JVM utiliza threads para coletar objetos abandonados na memória (Garbage Collector)