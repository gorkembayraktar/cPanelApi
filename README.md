# cPanelApi


// Instantiate the CPANEL object.
require_once "cPanelApi.php";





  $api = new cPanelApi("domain.com","username", "password");
  
  // Mail adresi oluşturmak
  echo $api->createEmail("hellomail", "newpassword;123.!<>>>>", "unlimited");
