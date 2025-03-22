# Task 5

## Install Maven
```bash
sudo apt install maven
```

![Screenshot from 2025-03-22 11-05-56](https://github.com/user-attachments/assets/4a778788-2264-44fa-8f73-47840573dd8f)

## Fork the repo on github

![Screenshot (19)](https://github.com/user-attachments/assets/df605cf3-8771-4952-aaad-40e984633ea5)


## Configure Jenkins
 - In Jenkins go to `configure jenkins` > `tools`
 - Locate JDK section
 - Uncheck `Install Automatically`
 - Name `Java 17`
 - Go to terminal and enter the command and get the java 17 path:

```bash
update-java-alternatives --list 
```

 - paste the java path in `JAVA_HOME`

![3](https://github.com/user-attachments/assets/05a6d873-85a8-421e-900c-82123b49c772)


## Add the pipeline script and build the pipeline
![4](https://github.com/user-attachments/assets/e179268b-bd65-4fa7-af6a-d4a66c4cf3a9)


## Verify the console to see the actions 

![Screenshot from 2025-03-22 10-54-26](https://github.com/user-attachments/assets/e8f60e18-51a9-45e7-8786-5723d05af192)

![Screenshot from 2025-03-22 10-53-42](https://github.com/user-attachments/assets/1dcda24e-381c-4c8f-a671-080aca022603)
