# __Nove de Julho__

Nove de Julho é um projeto open-source de ativismo cívico com foco na Assembleia Legislativa do Estado de São Paulo.

Seu objetivo é agregar e formatar conjuntos de dados da Alesp, como gastos na cota parlamentar, proposições apresentadas, leis aprovadas, presenças em sessões, andamento de comissões, lista de funcionários, salários, entre outros.

Com desenvolvimento iniciado em janeiro de 2019, Nove de Julho é desenvolvido por [rodolfo-viana](https://github.com/rodolfo-viana), com a colaboração de [cuducos](https://github.com/cuducos) e [jtemporal](https://github.com/jtemporal).

### Fonte dos dados

Os dados são coletados diretamente da Alesp por meio do [Portal dos Dados Abertos](https://www.al.sp.gov.br/dados-abertos/) ou, quando não disponíveis no portal, por meio de raspagem do site oficial da assembleia.

### Conteúdo

Os scripts estão em desenvolvimento. Há três prontos:

- `deputados.py`<br>
Retorna informações sobre os deputados estaduais, tais como nome, partido, telefone, e-mail, placa do veículo oficial...

- `gasto_cota.py`<br>
Retorna os gastos efetuados com o auxílio da verba de gabinete.

- `salarios_servidores.py`<br>
Retorna os salários dos servidores desde 2014.

Os scripts rodam com o auxílio de `toolbox.py`.

### Licença MIT

Copyright (c) 2019 Rodolfo Viana

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
