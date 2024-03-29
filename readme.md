Trabalho NI AWR - simulation rf system

nota final:19,3

[software - NI AWR]
https://www.awr.com/software/products/ni-awr-design-environment

[problema] 

Considere que está a adquirir dados através de um sensor e pretende transmiti-los sem fios. Para além disso, considere também que os dados deste sensor podem ser representados por uma sinusoide com uma frequência de 1 MHz e potência de 0 dBm. Para transferir este sinal terá de dimensionar, no programa NI AWR, o sistema de comunicação sem fios sendo que este é constituído por um upconverter e por um downconverter para as frequências desejadas. Neste sistema, terá de conseguir obter o sinal à saída, com uma potência mínima de -10 dBm, em que os restantes sinais do espectro devem estar no mínimo 40 dB abaixo do sinal desejado.
A frequência do oscilador local a ser utilizada é indicada na tabela em anexo (potência máxima de 10 dBm), em que terá também de incluir o 2º harmónico do oscilador (presente num oscilador real, mas adicionado no software através de um combiner), com uma potência 20 dB inferior à da frequência fundamental. O ruído de cada um dos blocos deve ser mantido como automático e a impedância dos mesmos terá de ser definida. Após introduzir o bloco que corresponde ao ganho das antenas e ao free space path loss, considere que também está a receber interferência (que terá de ser filtrada) à frequência indicada na tabela em anexo, com uma potência de -35 dBm. O ganho dos amplificadores utilizados terá de ser de 30 dB cada, no máximo.
No fim, terá de realizar um relatório que será enviado para avaliação em conjunto com o ficheiro do sistema desenvolvido no programa.
