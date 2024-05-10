**Repositório destinado ao estudo e consumos de API's**

## As API's possuem alguns elementos que servem á sua ultilização

_______________________________|**Ponto de Entrada**|___________________________________

é o endereço do serviço hospedado, que pode ser acessado através de um navegador ou uma 
ferramenta de consumo de API's.
**Exemplo**: <https://dadosabertos.camara.leg.br/api/v2>


__________________________________|**Recursos**|________________________________________
é o nome do serviço, que pode ser acessado através de um navegador ou uma ferramenta de consumo de API's.
**Exemplo**: <https://dadosabertos.camara.leg.br/api/v2/deputados>


_________________________________|**Parâmetros**|________________________________________
são os parâmetros que podem ser passados para a API, que podem ser acessados através de um navegador ou uma ferramenta de consumo de API's.
**Exemplo**: <https://dadosabertos.camara.leg.br/api/v2/deputados?sigla>

___________________________________|**metodos**|_________________________________________
São os modos de consumode uma API's.
**Exemplo**: <https://dadosabertos.camara.leg.br/api/v2/deputados?> 

            -POST: inserção (CREATE)
            -GET: consulta (READ)
            -PUT: atualização (UPDATE)
            -DELETE: exclusão (DELETE)
Para este projeto vamos usar o Node.js e o NPM (Node Package Manager):

    Node.js v20.13.0 LTS -> Long Term Suport (versão estável)
    NPX -> Node Package eXecuter (Executor de pacote do Node)

    TO-DO (documentar):

    Instalação e uso do Json Server: https://github.com/typicode/json-server
    Criação do .gitignore
    Utilidade dos arquivos package
    Criação do script "start" no package.json
    Observações em relação ao uso do JSON5 vs. JSON: https://github.com/json5/json5
    Instalação das extensões para formatação de arquivo .json5
    Chamada do script start com NPM ao invés do NPX
    O que é o Chocolatey (e porque não instalá-lo agora)