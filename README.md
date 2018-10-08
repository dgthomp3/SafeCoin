# SafeCoin

SafeCoin is a simple blockchain, cryptocurrency, wallet implementation.
NOTE: This project is in the Beta phase and as of right now, it's still in its testing phase.

## Requirements:
If you are starting a new project make sure you have some dependences and add these 
libraries to the project or classpath:
##### bcprov-ext-jdk15on-159.jar
##### beansbinding-1.2.1.jar
##### gson-2.6.2.jar
##### PlaceHolder.jar

###### If this is a continuing project you can run the following files:
Main.java - simulates two people with wallets to send coins to one another. This also runs a local P2P.
LoginPage.java - will be the start of the application allowing a user to log into their wallet and create an acc
CDClientUI.java - the GUI of SafeCoin's wallet

###### Directions to run
(Run on Netbeans)
1. Open Netbeans on both Computers (Computer A and Computer B)
2. On your Computer A, remove the multi line comment on line 662. This is important to have the genesis block give your
wallet some coins.
3. On Computer B keep everything as is.
4. Press run project on both computers.
5. Sign in or create an account when prompted.
6. Once you have successfully signed in enter the IP Address of Computer B in the prompt on Computer A; enter the IP Address of Computer A in the prompt on Computer B.
7. Once the connection is established you will be able to send/receive coins between the two computers, as well as view the transaction history. 

###### Editors notes
This application sometimes like to drop connection or fail to establish connection at all.
Checking the balance on Computer B doesn't seem to update the balance but it ends up in our transaction list.