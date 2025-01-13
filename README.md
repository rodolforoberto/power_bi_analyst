# Desafios

# Desafio Analisando dados de um Dashboard de Vendas no Power BI - Módulo 1

Entendendo o Desafio
 
Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas 😎
 
Neste repositório, insira todos os links e arquivos necessários para seu projeto, seja um arquivo de banco de dados ou um link para o template no Figma.
 
Dica: Se o expert forneceu um repositório Github, você pode dar um "fork" no repositório dele para organizar suas alterações e evoluções mantendo uma referência direta ao código-fonte original.
 
Instruções para entrega
Descrição do desafio: Vamos para o primeiro desafio com Power BI? Neste projeto você irá replicar duas páginas já criadas durante o curso com a sample disponibilizada. Acesse o link do Gihub para ter acesso aos dados: 

https://github.com/julianazanelatto/power_bi_analyst 

A terceira página, a qual vocês irão criar sozinhos, deve conter alguns visuais. Esse desafio visa treinar a habilidade de criação de visuais. Assim, você poderá criar familiaridade com esses recursos. Em módulos mais avançados iremos tratar do layout mais elaborado dos nossos relatórios.  

Muito bem, a terceira página é composta por: 

Visual mapa 1: Soma de sales e unidades vendidas por país 

Visual mapa 2: Soma de lucro (profit) por país 

Visual de pizza: Lucro por segmento 

 

Além disso: 

Verifique a disposição dos visuais no relatório 

Modifique os nomes dos visuais para algo mais claro e direto (de acordo com o contexto) 

Preste atenção aos campos que são utilizados como dicas de ferramentas  

Publique o relatório 

Compartilhe como suplemento no Power Point 

Caso não tenha Power Point, salve o projeto de Power BI  

 
Repositório Git
 
O Git é um conceito essencial no mercado de trabalho atualmente, por isso sempre reforçamos sua importância em nossa metodologia educacional. Por isso, todo código-fonte desenvolvido durante este conteúdo foi versionado no seguinte endereço para que você possa consultá-lo a qualquer momento:
 
https://github.com/julianazanelatto/power_bi_analyst

 
Bons estudos 😉

# Resposta ao Desafio

[Desafio Analisando dados de um Dashboard de Vendas no Power BI](https://github.com/rodolforoberto/power_bi_analyst/tree/main/M%C3%B3dulo%201/Desafio%20Analisando%20dados%20de%20um%20Dashboard%20de%20Vendas%20no%20Power%20BI)

</br>

# Desafio Criando Um Relatório Gerencial de Vendas com Power BI - Módulo 2

Entendendo o Desafio
 
Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas 😎
 
Neste repositório, insira todos os links e arquivos necessários para seu projeto, seja um arquivo de banco de dados ou um link para o template no Figma.
 
Dica: Se o expert forneceu um repositório Github, você pode dar um "fork" no repositório dele para organizar suas alterações e evoluções mantendo uma referência direta ao código-fonte original.
 
Instruções de Entrega do Desafio
Descrição do desafio: Você irá criar um relatório mais elaborado com base na sample financials do Power BI. Os arquivos de dados estão disponíveis no github: 

https://github.com/julianazanelatto/power_bi_analyst 

Fiquem atentos a: 

Estrutura definida 

Botões de navegação que fornecem navegabilidade 

Segmentadores utilizados e botões com imagem associado 

Utilize os indicadores e botões para selecionar diferentes visuais sobre um mesmo assunto 

 

Utilize os vídeos de passo a passo para criação dos elementos que compõem a primeira página do relatório: 

Objetos que definem o layout do relatório 

Gráficos (visuais) e os campos que os compõem 

Botões para navegabilidade 

Segmentadores de dados 

 

Lembre-se de: 

Criar a segunda página do relatório 

Publique o seu relatório no Power BI Service 

Caso você tenha familiaridade fique livre para utilizar outros artifícios nos botões e outros 

Submenta seu projeto através do link no github 

 
 

Bons estudos 😉

# Resposta ao Desafio

[Desafio Criando Um Relatório Gerencial de Vendas com Power BI](https://github.com/rodolforoberto/power_bi_analyst/tree/main/M%C3%B3dulo%202/Desafio%20Criando%20Um%20Relat%C3%B3rio%20Gerencial%20de%20Vendas%20com%20Power%20BI)

</br>

# Desafio Criando um Dashboard corporativo com integração com MySQL e Azure - Módulo 3

</br>

![Relatório Company Constraints](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Criando%20um%20Dashboard%20corporativo%20com%20integra%C3%A7%C3%A3o%20com%20MySql%20e%20Azure/Company%20Constraints/Company%20Contraints%20Relat%C3%B3rio.png)

</br>

O Desafio do projeto é pegar o banco de dados company_contraints, no github e fazer análise, transformação dos dados e gerar um relatório com o Power BI.

Foi sugerido a criação de uma instância no serviço da Azure da Microsoft, como para realizar o cadastro nesse serviço se faz necessário o uso de cartão de crédito. Não tenho como utilizar esse serviço. Portanto realizei a criação das tabelas e persistência dos dados localmente com o Mysql workbench, utilizando os scripts fornecidos.

Bom, com o banco de dados criado e os dados persistidos localmente, ao obter dados com o Power BI, com o conector instalado e acessando o banco de dados Azure_company do Mysql.

E de acordo com a orientação a ser realizada nos dados de acordo com o desafio, foi realizado os passos a seguir:

1 - Com a transformação dos dados no Power Query, foi analisado os dados e realizada remoção de colunas com os meta dados e colunas que não serão utilizadas. Nome  e tipo de dados foram verificados.

2 - Na tabela employee, a coluna Salary, foi alterada para o tipo Double preciso.
</br>A coluna Address, foi dividida por Number, Street, City e State com os seus tipos de dados Inteiro, Texto, Texto e Texto.
</br>A coluna supper_ssn, 2 linhas estavam como null, utilizei abstração, e adicionei “123456789” como gerente.
</br>
![Tabela Employee tratada](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Criando%20um%20Dashboard%20corporativo%20com%20integra%C3%A7%C3%A3o%20com%20MySql%20e%20Azure/Company%20Constraints/Azure_company_employee_tratada.png?raw=true)

3 -  Mescla das colunas da tabela base azure_company_employee, coluna Dno, com a tabela azure_company_department, com a coluna Dnumber.
</br>
![Menu de Mescla das Tabelas Employee e Department, coluna Dno e Coluna Dnumber](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Criando%20um%20Dashboard%20corporativo%20com%20integra%C3%A7%C3%A3o%20com%20MySql%20e%20Azure/Company%20Constraints/mescla_das_colunas_employee_department.png?raw=true)

</br>

Resultado da Tabela criada com a mescla, com o nome de azure_company employee_department, verifique que a coluna virou FLname, com a junção das colunas Fname e Lname, utilizando o espaço como separador de cada palavra. E a Coluna Department, mostra o nome de cada departamento atrávez da mescla de consulta.


![Resultado da Mescla Azure_company_employee_departamento](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Criando%20um%20Dashboard%20corporativo%20com%20integra%C3%A7%C3%A3o%20com%20MySql%20e%20Azure/Company%20Constraints/Azure_company_employee_department_mescla_FLname_Department_Tratada.png?raw=true)

Imagem a mesma de cima, com o foco no nome do colaborador e Departamento 

![Tabela Nome e Departamento](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Criando%20um%20Dashboard%20corporativo%20com%20integra%C3%A7%C3%A3o%20com%20MySql%20e%20Azure/Company%20Constraints/Azure_company_employee_department_mescla_FLname_Department.png?raw=true)

4 - Junção dos Nomes dos Colaboradores com os nomes dos gerentes, mescla da tabela azure_company_employee, colunas Supper_ssn  e Ssn

![Menu da mescla tabela employee coluna Super_ssn e ssn](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Criando%20um%20Dashboard%20corporativo%20com%20integra%C3%A7%C3%A3o%20com%20MySql%20e%20Azure/Company%20Constraints/azure_company_employee_super_ssn_ssn.png?raw=true)

</br>
Resultado da mescla das colunas.

![Resultado da mescla tabela employee coluna Super_ssn e ssn](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Criando%20um%20Dashboard%20corporativo%20com%20integra%C3%A7%C3%A3o%20com%20MySql%20e%20Azure/Company%20Constraints/azure_company_employee_super_ssn_ssn_resultado.png?raw=true)

</br>

Nome do colaborador e do gerente, com a mescla da consulta foi gerada a coluna e alterado para o nome de manager.

![Nome do colaborador e nome do gerente](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Criando%20um%20Dashboard%20corporativo%20com%20integra%C3%A7%C3%A3o%20com%20MySql%20e%20Azure/Company%20Constraints/azure_company_employee_super_ssn_ssn_zoom.png?raw=true)

</br>

5 - Mescla dos nomes do departamento e localização, mescla da tabela azure_company department, coluna Dnumber e azure_company dept_locations, coluna Dnumber

![Menu da mescla entre a tabela azure_company department, coluna Dnumber e azure_company dept_locations, coluna Dnumber.
](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Criando%20um%20Dashboard%20corporativo%20com%20integra%C3%A7%C3%A3o%20com%20MySql%20e%20Azure/Company%20Constraints/Azure_company_department_dept_locations_mescla.png?raw=true)

</br>
Resultado da mescla das tabelas.
Foi realizado a mescla de colunas pois as duas tabelas tem as mesmas colunas Dnumber, por este motivo não é apropriado utilizar o atribuir.

![Resultado da mescla das tabelas de Department e Dept_locations](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Criando%20um%20Dashboard%20corporativo%20com%20integra%C3%A7%C3%A3o%20com%20MySql%20e%20Azure/Company%20Constraints/Azure_company_department_dept_locations_mescla_resultado.png?raw=true)

</br>

6 - Agupamento para saber quantos colaboradores existem por gerente

![Agrupamento](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Criando%20um%20Dashboard%20corporativo%20com%20integra%C3%A7%C3%A3o%20com%20MySql%20e%20Azure/Company%20Constraints/Agrupamento.png?raw=true)

Resultado

![Resultado do Agrupamento](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Criando%20um%20Dashboard%20corporativo%20com%20integra%C3%A7%C3%A3o%20com%20MySql%20e%20Azure/Company%20Constraints/colaborador%20e%20gerente.png?raw=true)

</br>

# Desafio Star Schema - Universidade - Módulo 4

Objetivo:

Criar o diagrama dimensional – star schema – com base no diagrama relacional disponibilizado.

Modelo Disponibilizado 
![Modelo disponibilizado](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%204/Desafios%20de%20Projeto/der_universidade.png?raw=true)

Foco:

Professor – objeto de análise

Vocês irão montar o esquema em estrela com o foco na análise dos dados dos professores. Sendo assim, a tabela fato deve refletir diversos dados sobre professor, cursos ministrados, departamento ao qual faz parte.... Por aí vocês já têm uma ideia do que deve compor a tabela fato do modelo em questão.

Obs.: Não é necessário refletir dados sobre os alunos!

O que deve ser feito?

Deverá ser criada a tabela Fato que contêm o contexto analisado. Da mesma forma, é necessária a criação das tabelas dimensão que serão compostas pelos detalhes relacionados ao contexto.

Por fim, mas não menos importante, adicione uma tabela dimensão de datas. Para compensar a falta de dados de datas do modelo relacional, suponha que você tem acesso aos dados e crie os campos necessários para modelagem.

Ex: data de oferta das disciplinas, data de oferta dos cursos, entre outros. O formato, ou melhor, a granularidade, não está fixada. Podem ser utilizados diferentes formatos que correspondem a diferentes níveis de granularidade.

# Resposta ao Desafio - Star Schema - Universidade
![Resposta ao desafio Star Schema - Universidade](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%204/Star%20Schema%20-%20Universidade/Star%20Schema%20-%20Universidade.png?raw=true)

</br>

# Desafio Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX - Módulo 4

Desafio utilizando a tabela de Financial Sample, que é gerada pelo Power BI. Criação das tabelas dimensões e da tabela fatos, em um Star Schema.

Star Schema - Financials Sample

São 5 Tabelas Dimensões(D_Produtos_Detalhes, D_Produtos, D_Descontos,D_Detalhes e D_Calendario(Gerada com fórmula DAX) e Tabela Fatos(F_Vendas)

![Star Schema - Flinancial Sample](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%204/Modelando%20um%20Dashboard%20de%20E-commerce%20com%20Power%20BI%20Utilizando%20F%C3%B3rmulas%20DAX/Modelando%20um%20Dashboard%20de%20e-commerce/Star%20Schema%20-%20Financials.png)

</br>
Tabela Calendario Gerada com Formula DAX
A Fórmula utilizada foi:  D_Calendario = CALENDAR (DATE(2013,1,1),DATE(2015,1,1))

![Tabela gerada Calendário formula DAX e a formula utilizada](https://github.com/rodolforoberto/power_bi_analyst/blob/main/M%C3%B3dulo%204/Modelando%20um%20Dashboard%20de%20E-commerce%20com%20Power%20BI%20Utilizando%20F%C3%B3rmulas%20DAX/Modelando%20um%20Dashboard%20de%20e-commerce/Tabela%20Calendario%20gerada%20por%20DAX.png?raw=true)

</br>

Arquivo .pbxi e as pngs - [Arquivos](https://github.com/rodolforoberto/power_bi_analyst/tree/main/M%C3%B3dulo%204/Modelando%20um%20Dashboard%20de%20E-commerce%20com%20Power%20BI%20Utilizando%20F%C3%B3rmulas%20DAX)

</br>

# Criando um Dashboard Gerencial para Tomada de Decisões Com Power BI - Módulo 5

Desafio de Projeto - Atualizando Relatório Financeiro com Foco na Experiência do Usuário


Objetivo do desafio:

Modificar o relatório criativo, o primeiro que criamos juntos, focando na experiência do usuário. Acompanhe o vídeo para que você entenda o que foi feito neste processo. Além disso, leve em consideração os seguintes pontos:

· Posicionamento

· Contraste

· Proporção áurea

· Segmentação dos dados


Como comentamos no curso, não é uma regra rígida. Entenda os pontos e cria seu relatório levando os em consideração. Contudo, saiba quando você deve quebrar as regras. Isso vai trazer mais criatividade ao seu relatório. Esses pontos fora da curva deixam seu relatório mais interessante.


Próximos passos:

· Insira os botões de navegabilidade

· Modifique a segunda página de forma similar a demostrada no desafio para a primeira página

· Modifique os botões de navegabilidade a fim de destacar o focalizar e selecionar

· Criar os menus de navegabilidade em cada página

· O estilo dos botões é livre!

· O relatório é composto por 3 páginas

# Resposta do Desafio

[Criando um Dashboard Gerencial para Tomada de Decisões Com Power BI](https://github.com/rodolforoberto/power_bi_analyst/tree/main/M%C3%B3dulo%205/Criando%20um%20Dashboard%20Gerencial%20para%20tomada%20de%20Decis%C3%B5es%20com%20Power%20BI)





