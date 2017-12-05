#uz-bundle
 
Rest api bundle for booking.uz.gov.ua which allows to store search request in db and notificate user by email if required tickets appears on booking site.
Here is rest api to add tickets requests in datebase. 
Command to check booking site and send emails to users(should be hanged on cron) : 

    php symf-base/bin/console  uz:search-tickets

required params to add in parameters.yml:

    uz_base_url: https://booking.uz.gov.ua/
    uz_lang: en
    uz_admin_email: admin-email@gmail.com
    
    #your mailer params
    #your datebase params
    
Also youn need to install guzzle dependency

    composer require guzzlehttp/guzzle




    
