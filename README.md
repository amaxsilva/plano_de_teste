# Plano de Teste

**nome do sistema**
**nome empresa**

*versão x.x*

## Histórico das alterações

   Data    | Versão |    Descrição   | Autor(a)
-----------|--------|----------------|-----------------
dd/mm/aaaa |  x.x   | Release incial | Danielle Farias


## 1 - Introdução

Este documento descreve os requisitos a testar, os  tipos de testes definidos para cada iteração, os recursos de hardware e software a serem empregados e o cronograma dos testes ao longo do projeto. As seções referentes aos requisitos, recursos e cronograma servem para permitir ao gerente do projeto acompanhar a evolução dos testes.

Com esse documento, você deve:
- Identificar informações de projeto existentes e os componentes de software que devem ser testados.
- Listar os Requisitos a testar.
- Recomendar e descrever as estratégias de teste a serem empregadas.
- Identificar os recursos necessários e prover uma estimativa dos esforços de teste.
- Listar os elementos resultantes do projeto de testes.

Também é possível apresentar aqui o programa que será testado.

## 2 - Requisitos a Testar

Esta seção deve conter os casos de uso e requisitos não funcionais identificados como objetos dos testes ao longo do desenvolvimento do projeto.
Como, em geral, os requisitos a testar são obtidos diretamente dos requisitos do sistema, esta seção é concebida como opcional. Assim sendo, sempre que novos requisitos a testar, que não constem como requisitos do sistema, forem identificados ou, simplesmente, por questões de organização e clareza, esta seção deve ser preenchida.
Dependendo das informações disponíveis, essa seção pode começar a ser preenchida já nas primeiras iterações do ciclo de vida a partir do documento de requisitos.

Caso seja necessário, liste aqui os requisitos a testar subdivididos em casos de uso e requisitos não-funcionais.

### Casos de uso:

Identificador do caso de uso | Nome do caso de uso
-----------------------------|---------------------
id UC1                       |       nome UC1
id UC2                       |       nome UC2

### Requisitos não-funcionais:

Identificador do requisito   | Nome do requisito
-----------------------------|---------------------
id req1                      |      nome req1
id req2                      |      nome req2


## 3 - Tipos de teste

Esta seção deve conter os tipos de testes escolhidos para cada iteração do projeto.
Pode-se definir inicialmente apenas os tipos de testes que serão usadas na próxima iteração, mas é possível também já registrar eventuais tipos de teste que se espera utilizar nas demais iterações. 
Com base no guia de testes, indique os tipos de testes que melhor se adéquam aos requisitos, tipo da aplicação e seus recursos disponíveis e, caso necessário complemente ou forneça mais detalhes da técnica e dos critérios de completude sugeridos no guia para cada tipo de teste indicado.

- Teste de interface de usuário;
- Teste de performance;
- Teste de carga;
- Teste de stress;
- Teste de segurança e controle de acesso;
- Teste de instalação;
- Entre outros.

### 3.1 - Métodos da Classe 

Para teste de funcionalidade.
Aqui deve-se verificar se cada classe retorna o esperado.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            descreva aqui o objetivo
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade (x)
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.2 - Persistência de Dados

Para teste de integridade de dados e do banco de dados.
Aqui deve-se verificar se os dados não se perdem ao desligar o programa. Se o programa consegue se recuperar em caso de falha ou fechamento repentino.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se dados são mantidos após súbito desligamento do programa .
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema (x)
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.3 - Integração dos Componentes

Para teste de funcionalidade.
Aqui deve-se verificar se as classes e métodos conseguem fazer a integração entre elas para uma sequência de ações do programa.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            descreva aqui o objetivo
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração (x)
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.4 - Tempo de Resposta de API

Para teste de API.
Aqui deve-se verificar se o tempo de respostas das ações são consideradas aceitáveis, qual o cabeçalho, autenticação.
Aconselhavel usar a heuristica VADER

<br/>
<table>
    <tr>
        <th>
            V - Verbos
        </th>
        <th colspan="4">
            A - Autenticação
        </th>
        <th>
            D - Dados
        </th>
        <th>
            E - Erros
        </th>
        <th>
            R - Responsividade
        </th>
    </tr>
    <tr>
        <th>
  Verbos HTTP são comumente também conhecidos como métodos HTTP, essa parte consiste em testar os verbos aptos e não aptos para o endpoint. Coloco abaixo uma descrição básica dos principais verbos/métodos:

 - GET: Serve para buscar dados, pode ser cacheado e nunca deve ser usado com dados sensíveis.
 - POST: Pode criar e atualizar dados, possui um corpo/payload e preferencialmente não deve ter cache.
 - PUT: Usado para atualizar dados, pode possuir corpo, mas normalmente é usado no próprio path da url, que é o caminho para o identificador do recurso e a resposta bem sucedida pode ter corpo.
 - DELETE: Usado para excluir dados e pode possuir corpo para envio, mas normalmente é usado no próprio path da url com o identificador.
        </th>
        <th>
  Nesta etapa tudo se volta para o tipo de autorização que você utiliza, assim você vai saber quais os pontos que você tem que tomar cuidado, basicamente existem dois tipos mais populares de autorização que são:

 - Basic: credenciais codificadas em base64.
 - Bearer: tokens bearer para acessar recursos protegidos por OAuth 2.0.

Após isso, você pode realizar alguns cenários de testes utilizando alguns pontos:

 - Validar Token (Tipo de criptografia utilizar e testes de segurança).
 - Quais os recursos a API Key deve acessar.
 - Validar o não uso de Token, API Key ou Usuário e senha exposta na URL.
 - Testes de Token, API Key ou Usuário e senha inválido ou inexistentes.
 - Restrições de acesso assim que for autorizado.
        </th>
        <th>
    Nesta parte, olhamos para os dados que trafegam na API, sendo um payload de envio ou resposta de um endpoint. Neste momento podemos realizar alguns testes:

 - Tipagem: validação dos tipos do payload de envio e resposta com base na documentação
 - Paginação: Validar referencias para página anterior e seguinte, assim como a contagem de itens quando for um array.
 - Formato: Validar o tipo de retorno esperado pela API, os mais comuns são application/json e application/xml.
 - Tamanho: Validar o tamanho do envio e retorno da api, para não afetar ao tempo de resposta do endpoint.
        </th>
        <th>
    Aqui, avaliamos minuciosamente o códigos de resposta para cada erro e suas respectivas mensagens, também podemos incluir padrões de excessões para cada erros. Abaixo detalhamos os principais códigos de erros:

 - 400 Bad Request: servidor não entendeu a requisição feita,
 - 403 Forbidden: proibido o acesso em um determinado recurso.
 - 404 Not found: Servidor não encontrou o recurso solicitado.
 - 500 Internal Server Error: Erro genérico para quando o servidor encontrou algo em que ele não sabe lidar.
 - 503 Service Unavailable: quando o servidor se encontra em manutenção ou sobrecarregado.
* Nota importante: Definir com a equipe de desenvolvimento os padrões de retornos para os erros com mensagens e exceções, também definir quando acontece cada erro. Tenho sempre o costume de utilizar uma tabela DE/PARA em um excel para definir, excessão X deve ser o retorno Y.
        </th>
        <th>
    Nesta última etapa cuidamos de tudo que retorna em nossos serviços. Aqui podemos adicionar métricas de estrutura do seu projeto, que podem ser: Uso do CPU, Uptime dos serviços, Uso de memória da aplicação, capacidade de requisições por minutos e latência dos serviços, no qual pode ser encontrado em testes de carga e performance. Mas também podemos utilizar outro visão de análise que são as seguintes:

 - Tempo de resposta: Dada as ações que o endpoint pode realizar, analisar o tempo de resposta para essas ações e criar um padrão para o projeto.
 - Falha rápida (fail fast): É o conceito de interromper uma operação ao invés de tentar continuar ou executar as etapas seguintes do endpoint.
Concorrência: A realização de requisições em sequência ou ao mesmo tempo, afim de avaliar a carga que pode ser aplicada ao servidor.
        </th>
    </tr>
</table>
<br/>

### 3.5 - Animação

Para teste de funcionalidade (para games, principalmente, mas não somente).
Aqui deve-se verificar se as animações existentes no programa são disparadas quando devem e se seguem uma sequência lógica.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            descreva aqui o objetivo
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            ( ) manual
        </th>
        <th colspan="2">
            ( ) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta ( )
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>


## 4 - Recursos

Esta seção deve descrever os recursos humanos, de ambiente de teste (hardware e software) e de ferramentas de automatização de testes necessários para execução dos testes que devem ser descritos nas subseções que seguem.

### 4.1 - Ambiente de teste - Software e Hardware

Descreva aqui o hardware e sua configuração, e o software. Por exemplo, o sistema operacional, browsers, servidor web, etc.

### 4.2 - Ferramenta de teste

Descreva aqui as ferramentas específicas de teste usadas no projeto.


## 5 - Cronograma

Tipo de teste      | Duração | data de início | data de término
-------------------|---------|----------------|-----------------
planejar teste     |         | dd/mm/aaaa     | dd/mm/aaaa
projetar teste     |         | dd/mm/aaaa     | dd/mm/aaaa
implementar teste  |         | dd/mm/aaaa     | dd/mm/aaaa
executar teste     |         | dd/mm/aaaa     | dd/mm/aaaa
avaliar teste      |         | dd/mm/aaaa     | dd/mm/aaaa
