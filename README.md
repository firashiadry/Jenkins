# Jenkins
-------------------------------------------------------------------------------------------------
#### Jenkins job to build the simple-maven-project
### Prerequisites: 
Install maven ,use the following command:
```sh
apt install maven -y
```

### Job building steps:
1- Give your job a name and choose project type

2- Add a Description
![image](https://user-images.githubusercontent.com/31921743/120084306-bf9a6380-c0d7-11eb-86e0-d75c05164423.png)



3- Add the github repository url of the project
https://github.com/jglick/simple-maven-project-with-tests.git
![image](https://user-images.githubusercontent.com/31921743/120084277-7ea24f00-c0d7-11eb-825a-bdab058ceb78.png)
4- Add this command to build the project :
```
mvn -Dmaven.test.failure.ignore=true clean package
```
![image](https://user-images.githubusercontent.com/31921743/120084532-b27e7400-c0d9-11eb-86da-8c444bafb2d7.png)
5- Console Output
![image](https://user-images.githubusercontent.com/31921743/120084556-e8bbf380-c0d9-11eb-923a-319451672568.png)
6- Dashboard
![image](https://user-images.githubusercontent.com/31921743/120084590-26208100-c0da-11eb-848f-df8f2b467b19.png)




