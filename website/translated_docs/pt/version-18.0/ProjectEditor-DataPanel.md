---
id: version-18.0-data
title: Data
original_id: data
---

Esta seção permite que:

* define the data to include in your app (**Current data file** or **Production server data file**),
* automatically **regenerate data** each time you build your app or generate it manually, and
* filter data to vizualize in your app depending on **general filter queries** or **user information**.

![Data section](assets/en/project-editor/Data-tab-4D-for-iOS.png)

## Painel de fonte de dados

![Data section](assets/en/project-editor/Data-source-panel-4D-for-iOS.png)

This panel allows you to define your **data source**. You can choose to get data from the **Current data file** or from a **Production server**.

To secure access to the production server, a **key file** must be generated from the production server and physically communicated to the developer. This **key.mobileapp** file is available next to data in the MobileApps folder. Então o desenvolvedor pode selecionar a partir do editor de projeto para acessar dados do servidor de produção.

The **Production URL** must be entered from the **Publishing section** if you choose to get data from your production server.

Aqui também pode checar se o servidor está disponível e ativá-lo se necessário.<div markdown="1" class = "tips">
**NOTA **

* Tips are available to help you ensure the server works correctly.
* You can directly access the Publishing panel to define your production URL.
* To access production server data, a key file is required for secure communications.</div>

You can also define whether or not you want to **Regenerate data systematically** at each build.

When the **Do not regenerate data at each build** option is checked, you can save a considerable amount of time building your app. You can always generate your data manually by clicking on the **Regenerate Now button**.


## Painel Propriedades

![Data section](assets/en/project-editor/Properties-Panel-4D-for-iOS.png)

In this panel, you can define all the filters for each table based on **defined filter queries** or based on **user parameters**.

### Filtros de pesquisa

You can define filters per table which depend on field values:

* Primeiro ingresso sua pesquisa no campo dedicado escrevendo diretamente no "Campo de pesquisa". Também pode redatar sua pesquisa usando as abas Campos, Comparadores e Operadores, que estão disponíveis imediatamente sobre o campo de pesquisa quando estiver focado. Isso pode ser útil para definir sua pesquisa.

* Daí precisa validar sua pesquisa. Isso deve ser feito cada vez que modificar o filtro de pesquisa (uma pesquisa editada e não validada aparece em vermelho no editor de projeto).

* Finally, check the **Embed data into the built application** option to embed the data into the application when it's built. Deixe sem marcar se não quiser que os dados sejam integrados.

When a query filter is valid, a funnel icon appears indicating that the defined filter is based on a defined filter query.<div markdown="1" class = "tips">
**EXAMPLE**
In the **Filter query** field enter:
`FirstName = 'Lisa' & LastName = 'Hart'`
This query allows you to display only the records that include "Lisa" as FirstName and "Hart" as LastName.</div>


### Filtrado com filtros de informação de usuário

You can define filters depending on user information which you define in the Mobile App Authentication method:

* Da mesma forma que com filtros de pesquisa, primeiro deve definir sua pesquisa no campo apropriado.

* Para especificar que a pesquisa dependa da informação de usuário, apenas agregue ":" e a chave objeto `userinfo`.

* Depois valide sua pesquisa. Isso deve ser feito cada vez que modificar o filtro de pesquisa.

* Quando validar o filtro de pesquisa, aparece um botão que lhe permite agregar informação sobre os usuários no método [On Mobile App Authentication](http://doc.4d.com/4Dv17R3/4D/17-R3/On-Mobile-App-Authentication-database-method.301-3906587.en.html).

When a query filter is valid, a user icon appears to indicate that the defined filter is based on user information.<div markdown="1" class = "tips">
**EXAMPLE**
In the **Filter query** field enter:
CityName = :city
In the [On Mobile App Authentication](http://doc.4d.com/4Dv17R3/4D/17-R3/On-Mobile-App-Authentication-database-method.301-3906587.en.html) database method, enter:
`$response.userInfo:=New object("city";"Paris")`
This query allows you to display only the records which include "Paris" as CityName.</div> <div markdown="1" class = "tips">
**NOTA **
You'll find all the rules about query syntax in the [4D documentation](http://livedoc.4d.com/4D-Language-Reference-17-R3/ORDA-DataClass/dataClassquery.301-3907505.en.html).</div>

