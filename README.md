# devops-challenge

### setup the enviroment:
* install latest spring boot cli on linux:
```
   wget http://repo.spring.io/release/org/springframework/boot/spring-boot-cli/2.0.2.RELEASE/spring-boot-cli-2.0.2.RELEASE-bin.zip
   unzip spring-boot-cli-2.0.2.RELEASE-bin.zip
   rm -rf spring-boot-cli-2.0.2.RELEASE-bin.zip
   sudo vim /etc/profile
   export SPRING_HOME=/home/albarki/spring-2.0.2.RELEASE/
   export PATH=$SPRING_HOME/bin:$PATH
   source /etc/profile
   spring --version
```
* create an example rest api:
```
   $ spring init --build maven --groupId com.albarki.examples \
   --version 1.0 --java-version 1.8 --dependencies web \
   --name hola-springboot hola-springboot
   $ mvn spring-boot:run
```
* 
