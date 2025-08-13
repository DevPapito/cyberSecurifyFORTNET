# Conceitos de redes fortinet
____
COLISAO camada de ENLACE

    A colisao e um conceito aonde os quadros se conflitam, hoje os protocolos evitam esses formatos de devidas formas, juntos com os middled-devices
    inteligentes

    Existindo dos protocolos que foram os padroes para esse formato e um ainda muito usado o 
    CSMA/CD(Wired)(Carrier Sense Multipe Access with Collision Detection) e o CSMA/CA(Wireless)(Carrier Sense Multiple Access with Collision Avoidance)

    Ainda e usado para barrar colisao em rede Wireless, motivo e que nao a maneira de barrar colisao na transmissao Wireless, assim sendo exencial um
    protocolo para barrar. Ja o motivo do CSMA/CD(Wired) nao ser mais utilizado e o fator que Switchs modernos sendo eles Layer 2 ou Layer 3 ja possuem
    funcionamento de barramento para colisoes sendo Full-duplex ou Half-duplex 

____
Funcionamento de BARRAMENTO DE COLISAO CSMA/CA

    O CSMA/CA(Collision Avoidance) possui um funcionamento diferente do CSMA/CD(Collision Detection) pois a colisao nao e possivel de ser detectada
    entao o Computador utiliza o CSMA/CA para detectar se um envio de transmissao foi lancando, assim realizando um aguarde ate que o envio tenha
    sido concluido. Por esse motivo as redes Wireless somente <b>FUNCIONAM</b> em modo <b>HALF-DUPLEX</b> assim utlizando o <b>TDD</b>(Time Division Duplex)

    Existindo em aparelhos militares carrisimos a possibilidade da tecnologia WI-FI com FULL-DUPLEX tendo o controle digital, mas somente
    em nivel militar

____
RTS/CTS

    A um mecanismo opcional dentro do CSMA/CA(Collision Avoidance) aonde a RTS(Request To Send) que realiza uma requisicao(pedido para transmitir) do
    end-device na rede e a espera pelo CTS(Clear to Send) do Access Point da rede assim dando uma autorizacao para transmitir o envio. 
    Por fim ainda e recebido o ACK que e enviado pelo receptor do envio como uma confirmacao de pacote, o pacote e dado o nome de <b>Acknowledgment</b>
