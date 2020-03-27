# GenerateFullPackageXML

Script utilizado para gerar o package.xml contendo metadados que não suportam 

* [mdapi:describemetadata](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference_force_mdapi.htm)
* [mdapi:listmetadata](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference_force_mdapi.htm)



### Dependencias

* [Bash shell](https://fr.wikipedia.org/wiki/Bourne-Again_shell)
* [jq](https://stedolan.github.io/jq/)
* [Salesforce CLI](https://developer.salesforce.com/tools/sfdxcli) 


## Como utilizar

    $ GenerateFullPackageXML.sh <APIVERSION>  <OUTPUTFILE>
  
  
 Exemplo
 
    $ GenerateFullPackageXML.sh <APIVERSION>  <OUTPUTFILE> <ORGALIAS> <RESTRICTEDMEDATADAFILENAME(Optional)>
    
    Exemplo: 
    
    $ GenerateFullPackageXML.sh 45.0 ./Package.xml OrgAlias
   

## Maiores detalhes:  

[Generate a full Package.xml using the Salesforce CLI](https://medium.com/@medben/generate-a-full-package-xml-using-the-salesforce-cli-9e2b4e404569)
