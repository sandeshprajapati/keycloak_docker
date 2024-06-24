# Get started with Keycloak on Docker
To start using the keycloak, we should be have docker installation in your system
- install docker using following link - https://docs.docker.com/desktop/install/windows-install/
- once docker is installed in your system, please start the docker in window system
# Now we are ready to install keyclock
- open the cmd and run the following commnad in terminal
- docker run -p 8080:8080 -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=admin quay.io/keycloak/keycloak:25.0.1 start-dev
- Here KEYCLOAK_ADMIN and KEYCLOAK_ADMIN_PASSWORD you can take as your wish


