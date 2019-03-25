# SG_EmployeePortal
I have created Employee Portal UI code using angular2 and backend srvice using spring boot.
UI has registration form which can be filled and after submitting submit button rest service is called and json response is returned from service which i have displayed on UI.
Its just a very simple use case .I have not taken care for edge cases.But it can be handeled.

run command for running UI and backend-
for running Ui-- import project in visual studio and run this command -- ng serve
which will download all dependencies required.


Command for running backend services-
import backend project in STS or eclipse and just type below request from postman-

request body-
{
	"firstName":"praveen",
	"lastName":"patel",
	"gender":"male",
	"deteofBirth":"july",
	"department":"BT111"

}


URL- http://localhost:9094/employee



please let me know in case of any concerns or error.
