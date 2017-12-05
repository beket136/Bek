#uz-bundle
 

Rest api wrapper bundle for booking.uz.gov.ua allows to store search request in db and notificate user by email if required tickets appear booking site.

required params to add in parameters.yml:

    uz_base_url: https://booking.uz.gov.ua/
    uz_lang: en
    uz_admin_email: admin-email@gmail.com
    
    #your mailer params
    #your datebase params
Also youn need to install guxxle dependency composer require guzzlehttp/guzzle



    