# angular-bootstrap
Bootstrap an Angular-CLI project.

### Steps
1. Create a new Angular app:
  
    * Choose a location for the app and run:
  
          ng new my-new-app

2. Excecute the application:

    * Change directory to the root of the app:
  
          cd my-new-app
  
    * Start the server, either using **angular-cli**, or using **npm**:
  
      a. Using **angular-cli**
    
          ng serve
  
      b. Using **npm**
  
          npm start
   
    * Both commands will run the app. Once the app has compiled and the server is up and running, open the server url in a browser: http://localhost:4200
    
3. Create page components:
    
    **HOME COMPONENT**
      * Component only
      
            ng g c components/home --spec=false -is
          
      * Component + tests only
      
            ng g c components/home -is
       
      * Component + tests + styles
      
            ng g c components/home
            
      * Check that `my-new-app/src/app/app.module.ts` has been updated with the component.
  
    **SHARED COMPONENT**
      * Component only
      
            ng g c components/shared/navbar --spec=false -is
          
      * Component + tests only
      
            ng g c components/shared/navbar -is
       
      * Component + tests + styles
      
            ng g c components/shared/navbar
            
      * Check that `my-new-app/src/app/app.module.ts` has been updated with the component.
  
4. Create service components

    **SERVICES**
      * Service only 
        
            ng g s services/myservice --spec=false
          
      * Service + tests
    
            ng g s services/myservice
          
5. Create pipes

    **PIPES**
      * Pipe only
    
            ng g p pipes/mypipe --spec=false
          
      * Pipe + tests
    
            ng g p pipes/mypipe
  
1. Manage resources in a central location.
    * Copy resources to `my-new-app/src/assets`
    
