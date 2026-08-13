# VidaPlena - Sistema de Gestão de Clínica

Sistema feito em Java para gerenciar uma clínica multidisciplinar. Dá pra cadastrar pacientes, profissionais, agendar consultas, registrar atendimentos e processar pagamentos.

## Tecnologias
* Java
* Orientação a Objetos (POO)
* Tratamento de exceções
* JDK 11+

## O que dá pra fazer
* Cadastrar pacientes (mínimo ou completo) e complementar depois
* Cadastrar profissionais por especialidade (fisioterapia, psicologia, nutrição, clínica geral)
* Agendar consultas por profissional ou por especialidade
* Cancelar e remarcar consultas
* Registrar atendimentos com prontuário
* Processar pagamentos em dinheiro, cartão ou convênio
* Desativar pacientes
* Gerar relatórios (geral, por profissional, por período, financeiro, unificado)
* Exportar dados do sistema

## Como compilar e rodar

Precisa ter o JDK 11 ou superior. No terminal entra na pasta src e roda:

```java
javac *.java
java Main
```

## Como usar

O sistema funciona por menus no terminal. Ao abrir aparece o menu principal:
* 1 - Pacientes (cadastrar, buscar, complementar, desativar)
* 2 - Profissionais (cadastrar, atualizar dados)
* 3 - Consultas (agendar, cancelar, remarcar)
* 4 - Atendimentos (registrar com observações e diagnóstico)
* 5 - Pagamentos (dinheiro com 5% desconto, cartão até 6x, convênio)
* 6 - Relatórios (geral, por profissional, período, financeiro, unificado, exportar)
* 0 - Sair

Pra agendar uma consulta precisa ter o paciente e o profissional cadastrados antes. Pra registrar pagamento a consulta precisa ter sido atendida.

## Observação

Desenvolvido em dupla como projeto acadêmico.
