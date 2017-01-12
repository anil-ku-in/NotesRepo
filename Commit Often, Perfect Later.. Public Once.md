**Commit Often, Perfect Later.. Public Once**

composer create-project symfony/framework-standard-edition my_project_name "2.8.*"

php app/console debug:router

php app/console cache:clear

php app/console doctrine:database:create

php app/console generate:bundle ##annotation 

php app/console generate:bundle --namespace=Ens/JobeetBundle --format=yml

php app/console generate:controller ##yml
A ##yml <===============Create Entity

php app/console doctrine:generate:entities EnsJobeetBundle 
  <======Update Entioty
  
php app/console doctrine:generate:entities AppBundle/Entity/Product

php app/console generate:doctrine:form AppBundle:AllFields

php app/console doctrine:schema:update --force

php app/console cache:clear

php app/console server:run

git push --set-upstream origin develop-cyx-anil

 php app/console server:run 127.0.0.1:8001

$('body').on('click', '#getInvoicesGrid', function(){
    
});