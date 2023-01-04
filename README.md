Additional compile steps needed need to be documented in a README.md

Created a Spring Boot REST app that exposes endpoints:
>> Upload, view and delete images after authorizing the username/password.
>> Associate the updated list of images with the user profile.
>> View the User Basic Information and the Images

1.I can design templates using iReports Software but for this code got templates from google site.
2.Image configs are under resources folder in project.

>>Leverage the Imgur API i.e. the Spring Boot APP should integrate with Imgur API to upload, view and delete the images
https://apidocs.imgur.com/

1.This part was time consuming for me because of configs in my machine.

App Requirements:
1.Used JPA to store the user information with user name and password, retrieve the user name and password to authenticate the user.
2.The requirements were implemented using the REST API’s.

Other Notes:
• Used GitHub for deploying project.
• Good coding practices (logging, comments, test cases, domain driven design, 3-layer architecture – Controller,
Service, Repository) are followed.
• Used some 3rd party libraries.
