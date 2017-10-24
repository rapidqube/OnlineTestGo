"# OnlineTestGo" 

 => Technology used:- golang
 
 => Prerequisite:-
 
  1)git 
  
  2)golang
  
  3)MySql

 => deployment process to run application:-
 
  1)git clone <repository-url> 
  
  2)cd folder name
  
  3)go run (file name)

  Description of project:-
  
  The purpose of the system is to develop Online Examination System., used to test the Domain knowledge of the students, and employees with respect to the particular technology. The manual procedure used for conducting exam is time consuming process and error prone due to human limitations. The System purpose is to completely automate the old manual procedure of conducting exam to Online Web Based Examination System.

run following command to after cloning

$> go run main.go

you should be able to hit the web service using curl/ Rest client

Sample Request

URL : hitting http://<address>:<port>/registerUser

Header :
accept: application/json
accept-encoding: gzip, deflate
accept-language: en-US,en;q=0.8
content-type: application/json
user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2883.87 Safari/537.36


payload : 

{
  "fname":"yourfirstname",
  "lname":"yourlastname",
  "phone":"123456789",
  "email":"somone@something.com",
  "test":"Java"
}


