## Funcionamento da PCB ##  

### Trilhas e Conexões ###  
As trilhas em azul representam as conexões condutoras da PCB, substituindo os fios de ligação que seriam usados em um circuito montado em protoboard.  
Trilhas mais largas são aplicadas em regiões onde há maior circulação de corrente, especialmente na entrada e saída do regulador **7805**, garantindo menor resistência e melhor desempenho elétrico.  

A disposição dos componentes foi projetada para proporcionar um fluxo lógico da corrente elétrica, seguindo esta sequência:  
1. Entrada AC (**J2**)  
2. Retificação na **ponte retificadora (BR1)**  
3. Filtragem pelo **capacitor C1**  
4. Regulação da tensão pelo **7805 (U1)**  
5. Saída estabilizada de **5V DC pelo conector T1**  

Além disso, o **LED** serve como um indicador visual do funcionamento correto da fonte de alimentação.  

### Conclusão ###  
O layout da PCB foi otimizado para garantir um circuito compacto e eficiente. As trilhas foram organizadas de forma a minimizar o comprimento das conexões, reduzindo interferências eletromagnéticas e perdas de energia.  
Com esse design, a placa pode ser fabricada e utilizada como uma fonte de alimentação confiável de **5V DC** para diversos projetos eletrônicos.  

<img src="PCB.jpg">
