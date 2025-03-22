# Task 5

## Install Maven
```bash
sudo apt install maven
```
![image](https://github.com/user-attachments/assets/a1c7b760-d02d-403d-8213-48898f1ce463)


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

![Uploading WhatsApp Image 2025-03-22 at 14.26.43_53bf83ad.jpg…]()


## Fork The Repo and build the pipeline

![Uploading WhatsApp Image 2025-03-22 at 14.26.43_7148b530.jpg…]()
