For the last 3 years, I have focused on reengineering applications based on JSP, Java 8, JQuery and Bootstrap, to modern frameworks to speed up and enhance their results. 	 

I have been working on two interrelated applications: agricultural accounting, traceability and food safety; under the software as a service modality.  

Each of the applications supports multiple tenants. Each tenant can define multiple companies. Each company can define multiple branches. In the traceability application each branch can define multiple agricultural units or production units. I laid the foundations to incorporate the control of IoT devices or sensors. 					 

I equipped the applications with a machine learning module to provide data, information on accounting and laws. In the case of traceability, I provided information on nutrition, pruning, harvesting, good agricultural practices, among other topics. 				 

To achieve a deep impact on the end user, for the frontend I chose to code with TypeScript and Angular 14, using impact libraries such as handsontable, summernote, angular forms and bootstrap as my responsive CSS library. The applications are ready to run on nginx, Docker container or Kubernetes pods. 					 

I designed a mobile application using Ionic and Angular 18, saving designing time using the same components and services already done in the main application. 				 

To control all the frontend requests, I designed the backend with Jakarta EE 10, OpenJDK Azul Zulu 17, MicroProfile, MicroStream to handle in memory data base, Jakarta Persistence, JDBC, and a set of SQL queries to answer and build the machine learning module. 		 

For the REST endpoints security, I designed a way to encrypt in frontend using cryptoJs and the corresponding class in backend to decrypt the security data.  

The backend is divided into about 20 microservices running on Payara 6 applications server. Payara 6 has a MicroProfile module that together with the microprofile-config file in the application can define variables that function as Spring's @Profile, but wider. The REST endpoints produce and consume Json objects. If I need to communicate with other services, I use MicroProfile interfaces to achieve it. 					 

As in the frontend each microservice is designed to run on the Application Server or be deployed in a Docker container with payra-micro runtime or inside Kubernetes pods. 			 

Currently I am preparing to expand my knowledge of cloud native and devOps.
