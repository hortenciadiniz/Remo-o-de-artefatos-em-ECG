# Removal-of-ECG-artifacts

* Federal University of Campina Grande

* Hortência Diniz Dultra e Silva - 17/11/23

* Remoção de Artefatos do ECG.

* Livro-Texto: Biomedical Signal Processing, Rangaraj. Wiley

* 3.12 Application: Removal of Artifacts in the ECG

No contexto de um eletrocardiograma (ECG), artefatos referem-se a interferências indesejadas ou sinais anômalos que aparecem nos traçados do ECG e que não representam a atividade elétrica do coração. Esses artefatos podem ser causados por vários fatores externos que interferem com a aquisição adequada dos sinais cardíacos.
Os artefatos podem ser causados por fatores como:

* Movimentos Musculares: contrações musculares, especialmente aquelas causadas pelo tremor ou movimento do paciente durante a gravação do ECG, podem criar artefatos.

* Má Contato dos Eletrodos: se os eletrodos não estiverem devidamente fixados à pele do paciente ou se houver má condutividade elétrica entre o eletrodo e a pele, isso pode resultar em artefatos.

* *Interferência Elétrica:* ruídos elétricos provenientes de fontes externas, como lâmpadas fluorescentes, dispositivos eletrônicos próximos ou cabos elétricos, podem causar interferências nos sinais do ECG.

* Má Qualidade do Equipamento: Equipamentos defeituosos ou mal calibrados podem introduzir artefatos nos traçados do ECG.

* Movimentos do Paciente: Se o paciente se mover durante a gravação do ECG, isso pode causar artefatos nos resultados.

* Interferência Eletromagnética: Equipamentos médicos ou dispositivos eletrônicos presentes nas proximidades do local onde o ECG está sendo realizado podem gerar interferências eletromagnéticas.

Este projeto visa retirar os artefatos de um ECG e nele, temos que tirar os artefatos gerados pela linha elétrica da rede.

No Brasil: f=60Hz

O sinal ECG foi pego de uma base de dados disponibilizada no PVAE.

![ECG after both filters](./ECG_COMB.png "ECG after both filters")


![ECG Original](./ECG_FFT.png "ECG Original")


![ECG after High Pass Filter](./ECG_HIGH.png "ECG after High Pass Filter")


![ECG after Low Pass Filter](./ECG_LOW.png "ECG after Low Pass Filter")


![ECG Original](./ECG_ORIGINAL.png "Áudio Result")

