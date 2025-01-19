# 🖥️  Projeto-SAP-1

### Objetivo do Projeto: 
<p>O objetivo deste projeto é desenvolver e implementar circuitos digitais que compõem o modelo do computador SAP-1, utilizando componentes como registradores, Unidade Lógica e Aritmética (ULA), e outros elementos essenciais. O SAP-1 é um computador didático projetado para ensinar os princípios fundamentais de arquitetura de computadores e funcionamento de circuitos digitais.</p>

# 🏗️ Construindo a Arquitetura do SAP-1

O SAP-1 é um computador simples, e nos ensina muito sobre como os computadores funcionam por dentro. Ele tem registradores, memória, barramentos e tudo mais, mas tudo de um jeito bem simples pra gente conseguir entender, isso torna ele uma ótima ferramenta didática.

### ⚙️ Como Funciona?
O SAP-1 funciona de forma bem organizada e os barramentos são a principal forma de comunicação entre os diversos componentes. Aqui vai um resumo rápido de como as coisas se conectam:

- **Contador de Programa (PC)**: Rastreia o endereço da próxima instrução.
- **Memória (RAM + REM)**: Guarda os dados e instruções. O contador de programa manda o endereço, a memória devolve a instrução.
- **Registrador de Instruções (IR)**: Armazena a instrução que está sendo processada no momento.
- **Acumulador (ACC)**: Guarda os resultados intermediários das operações. É tipo o braço direito do somador-subtrator.
- **Somador-Subtrator**: Faz as operações matemáticas básicas (soma e subtração).
- **Unidade Lógica e Aritmética (ULA)**: É responsável por realizar cálculos e operações matemáticas. Trabalha junto com o acumulador, que manda os valores e recebe o resultado. É como o "cérebro matemático" do sistema.

Ah, e as instruções são simples: LDA (carregar no acumulador), ADD (somar), SUB (subtrair), OUT (mostrar o resultado) e HLT (parar). Essas poucas instruções já dão pra fazer muita coisa legal! ✨


## 💪 Desafios e Aprendizados
Construir o SAP-1 foi uma experiência desafiadora. Aqui vão alguns pontos que me deram trabalho:

### Integração dos Componentes
Conectar tudo foi bem tenso. A arquitetura é simples, mas qualquer errinho nos sinais ou conexões pode bagunçar o circuito inteiro. Por exemplo, ligar os registradores, memória e sinais de controle foi um baita quebra-cabeça.

### Sincronização (o famoso clock)
Uma das partes mais difíceis foi entender como sincronizar os sinais de controle. Tudo precisa acontecer no tempo certo: o contador de programa incrementa, a memória é acessada, os dados vão pros registradores... É muita coisa pra orquestrar.

### Compatibilidade de Bits
Outra dificuldade foi lidar com erros de incompatibilidade de bits, especialmente nos casos em que dependiam de entradas, saídas ou barramentos. Esses detalhes deram muito trabalho, porque se os tamanhos ou os sinais não estavam corretos, o circuito simplesmente não funcionava.

---
### 🤝 Apoio 
Nisso tudo, tive o apoio do meu professor, que disponibilizou materiais super úteis no GitHub dele (fredcwbr). Esses conteúdos foram essenciais pra entender melhor o funcionamento dos circuitos e evitar alguns erros comuns. Recomendo dar uma olhada 👀

---

## 🛠️ Ferramentas e Referências
Eu usei o software Digital pra montar os circuitos, que é uma ferramenta bem prática pra testar e visualizar tudo funcionando. Também consultei bastante o livro *Microcomputadores e Microprocessadores* do Malvino, especialmente o capítulo 10, que explica bem como o SAP-1 funciona.

---

## 🎯 Conclusão
Construir o SAP-1 foi desafiador, mas também muito recompensador. Aprendi na prática como as instruções são processadas, armazenadas e executadas. Além disso, deu pra ver na real como todo computador ainda segue os mesmos princípios básicos. Se você também estiver construindo o seu SAP-1, eu fiz esse README para compartilhar que erros fazem parte do processo. Cada ajuste é um passo a mais para entender melhor 💡


