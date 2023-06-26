# Organizador de arquivos e fotos em Datas

## Tabela de conteúdos

- [Contextualizacao](#contextualizacao)
- [Utilização](#utilizacao)
- [Licença](#licenca)

## Contextualização <a name = 'contextualizacao'></a>

<div align='justify'>
    <p>
        Por conta de uma necessidade de organização de arquivos e/ou fotos que precisam ser transferindo-os entre pastas e/ou nuvens (<code><a href='https://www.microsoft.com/pt-br/microsoft-365/onedrive/online-cloud-storage'>OneDrive</a></code> para <code><a href='https://www.google.com/intl/pt-br/drive/about.html'>Google Drive</a></code>, no caso) o ideal seria realizar tal separação por pasta usando o padrão do ano <code>YYYY</code> e,uma subpasta com os meses <code>mm</code> após por dia <code>dd</code> porém, apesar dessa organização, cada arquivo deverá estar nomeado no padrão <code>YYYY-mm-dd</code> para, que seja possível um reprocessamento apenas para cuidar da organização.
    </p>
    <p>
        Como isso daria um certo trabalho, estou buscando automatização para manter a organização sem demandar esforço humano para que consiga tal organização.
    </p>
    <p>
        Tal projeto se torna possível pois, nas propriedades dos arquivos/fotos possui a data em que o arquivo foi criado, quando não existir essa informação possa ser interessante pegar a data de modificação. Porém, deverá ser analisado qual das informações seria interessante usar pois, quando se copia/move um arquivo de lugar ele refaz a data da criação ou seja, é interessante a modificação nesses casos.
    </p>
</div>

## Utilização <a name = 'utilizacao'></a>

<div align='justify'>
    <p>
        Para o bom funcionamento do código de <code>MVP</code> basta mover os arquivos desejados dentro da pasta:
    </p>
</div>

`$ .\Código\Entrada`

<div align='justify'>
    <p>
        Para que seja possível executar o código <code>MVP</code>:
    </p>
</div>

`$ .\Código\Processamento\MVP.ipynb`

<div align='justify'>
    <p>
        Como saída, ele criará as respectivas pastas seguindo a hierarquia:
    </p>
</div>

`$ .\ano\ano-mes\ano-mes-dia\ano-mes-dia (frequencia).extensao`

<div align='justify'>
    <p>
        Na respectiva pasta de saída:
    </p>
</div>

`$ .\Código\Saída`

<div align='justify'>
    <p>
        <b>P.S.</b>: Possa ser necessário criar as pasta de <code>Entrada</code> e/ou <code>Saída</code> dentro do repositório:
    </p>
</div>

`$ .\Código`

## Licença <a name = 'licenca'></a>

<div align='justify'>
    <p>
        <a href='https://github.com/murilochaves/organizador-arquivos/blob/main/LICENSE'>Licença MIT</a>
    </p>
    <p>
        Copyright (c) 2023 Murilo Chaves Jayme
    </p>
    <p>
        Permissão é concedida, gratuitamente, a qualquer pessoa que obtenha uma cópia deste software e dos arquivos de documentação associados (o 'Software'), para negociar sem restrições no uso, cópia, modificação, fusão, publicação, distribuição, sublicenciamento e/ou venda de cópias do Software, e permitir que as pessoas a quem o Software é fornecido o façam, sujeitas às seguintes condições:
    </p>
    <p>
        O aviso de direitos autorais acima e este aviso de permissão devem ser incluídos em todas as cópias ou partes substanciais do Software.
    </p>
    <p>
        O SOFTWARE É FORNECIDO 'COMO ESTÁ', SEM GARANTIA DE QUALQUER TIPO, EXPRESSA OU IMPLÍCITA, INCLUINDO, MAS NÃO SE LIMITANDO ÀS GARANTIAS DE COMERCIALIZAÇÃO, ADEQUAÇÃO A UM PROPÓSITO ESPECÍFICO E NÃO VIOLAÇÃO. EM NENHUMA CIRCUNSTÂNCIA, OS AUTORES OU DETENTORES DE DIREITOS AUTORAIS SERÃO RESPONSÁVEIS POR QUALQUER RECLAMAÇÃO, DANOS OU OUTRA RESPONSABILIDADE, SEJA EM AÇÃO DE CONTRATO, DELITO OU DE OUTRA FORMA, DECORRENTE, FORA OU EM CONEXÃO COM O SOFTWARE OU O USO OU OUTRAS TRANSAÇÕES NO SOFTWARE.
    </p>
</div>

