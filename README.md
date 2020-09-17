# Kit Easy FPGA

Documentação em português do kit Easy FPGA 2.1 com FPGA Altera (Intel) Cyclone IV EP4CE6E22C8. Em tempo, o "N" no final do código gravado no componente é apenas algo como a versão "normal" do componente.

Esse Kit Easy FPGA tem um baixo custo e é bem popular nos sites de compras chineses. Como a documentação que vem junto com o kit deixa bastante a desejar, a intenção deste repositório é fornecer um pouco de documentação confiável em português para auxiliar aqueles que adquiriram (ou pensam em adquirir) esse produto.

![KitFPGAEasy_small](https://user-images.githubusercontent.com/39290223/92793804-1cf15780-f385-11ea-8933-53bfdfd7c324.jpg)

Os arquivos "EasyFPGA-InformaçõesImportantesePinagem" (PDF e XLSX) possuem a pinagem e comentários relevantes. Por exemplo configurar a tensão para 3,3V LVTTL e configurar os pinos não usados como "input tri-stated".

Há também arquivos em VHDL de exemplo. Até o momento:

- PortaE: um template básico de VHDL com uma porta lógica E de forma que o comportamento testado no kit bata com a função, uma vez que as chaves emitem nível lógico "0" quando acionadas e os leds também são acionados com "0")

- Conv_7Seg: um conversor para o display de 7 segmentos acionado a partir das chaves. Sem multiplexação do display.

A ferramenta de desenvolvimento utilizada é a Intel Quartus Prime Lite, versão gratuita, que pode ser obtida em https://fpgasoftware.intel.com/?edition=lite.

Voltando à placa, uma breve análise mais pessoal. Comprei a minha na virada de 2016 para 2017, mas o mesmo modelo ainda é vendido em setembro de 2020 quando publico este repositório. Eu a utilizo para algumas demonstrações e preparar alguns experimentos para aulas de Sistemas Reconfiguráveis. Alguns prós e contras na minha perspectiva:

  * Prós:
  ** ótimo custo x benefício;
  ** possui diversos periféricos integrados previamente;
  ** disponibiliza todos os pinos para conexão externa / expansão;
  ** é capaz de rodar o NIOS, o soft processor da Intel.

  * Contras:
  ** a documentação é muito ruim e suporte do fabricante inexistente;
  ** os botões e chaves (dip switch) estão ligados juntos, não sendo possível usá-los de modo independente. Isso obriga a frequentemente usar uma proto-board e colocar alguns botões externos.

Em meu site e no canal do YouTube há mais conteúdos sobre Computação e Lógica Reconfigurável, PLD, FPGA, VHDL, etc.

- Site: http://prof.valiante.info/disciplinas/sistemas-digitais

- YouTube: https://www.youtube.com/channel/UCRc9RVFIidacP89rUTiXxwA



