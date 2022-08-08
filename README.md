# cPanelApi


   
    require_once "cPanelApi.php";




 ## Instantiate the CPANEL object.
      $api = new cPanelApi("domain.com","username", "password");
  
  ## Mail adresi oluşturmak
      echo $api->createEmail("hellomail", "newpassword;123.!<>>>>", "unlimited");
