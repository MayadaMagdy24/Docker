# Docker

 Create a custom image with the following specs:
 
• Base image: postman/newman:5.3.1-alpine

• Update/upgrade the image packages to the latest.

• Globally Install node modules: newman-reporter-csvallinone

• Install extra packages: curl zip ping

• Set the DNS explicitly to 8.8.8.8 & 1.1.1.1

• Remove the installation cache.

• Set an environment variable NODE_PATH to have the value
/usr/local/lib/node_modules

• Set working directory to /etc/newman

• Set the entry point to newman

-----------------------------------

- Dockerfile 

![image](https://github.com/MayadaMagdy24/Docker/assets/93229250/c0a28076-e7f3-46eb-875e-c9f3a1fc4e98)

-------------------------------------

- entrypoint file
  ![image](https://github.com/MayadaMagdy24/Docker/assets/93229250/ae04480e-023f-445a-a070-10621037bb50)

-----------------------------------

- Image after I build it.

  ![image](https://github.com/MayadaMagdy24/Docker/assets/93229250/37b98e14-3a02-4f69-9a3f-d7a93dcce74c)

-------------------------------------


