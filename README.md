<img width="550" alt="logo" src="https://github.com/user-attachments/assets/2fec92f6-f20d-4f42-9346-3c176a73c7bb" />
 
#

Project made to monitor plants in greenhouses using 6 different sensors: air quality, light quality, temperature, air humidity, soil humidity, and air pressure.
You need to set up your own greenhouse with sensors, and then you can connect to it via this application to see visualized real-time values provided by the sensors. Sensor values are highlighted with colors to indicate whether the current value is within the normal range.

![allHouses](https://github.com/user-attachments/assets/d81ee2a2-0c48-4210-b2d4-3cea70830e79)

Every connected greenhouse has its own personal page, where more detailed information is shown about the normal range for each sensor and its accessibility. The history of previous sensor values can be viewed in a graph and table by selecting the desired time interval. Every user with the appropriate access can also add photos of the plant to the gallery.

![personalPage](https://github.com/user-attachments/assets/57e80f94-90d3-4cef-b31d-9387369c1be7)

The application supports adding and monitoring multiple greenhouses by multiple users with different roles to regulate access permissions. The admin role includes functionality to manage users and view the access events audit log.

![users](https://github.com/user-attachments/assets/9c6a2161-3079-4a80-9a8e-2b1fcde5b9f5)

<img width="949" alt="auditLog" src="https://github.com/user-attachments/assets/a8398002-85c9-4591-881a-4a4cb13cadfd" />

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Execute "mvn spring-boot:run" to start the Plant Health project and connect to
http://localhost:8080/ to access the Plant Health web application. You may login
with "admin" and "passwd".

For additional information regarding Databases and Accesspoints, please refer to their respective folders where you will find dedicated README.md files.

## Contributors:
- Elizaveta Terente
## Requirements
- Java 17
