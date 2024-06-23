Disclaimer: in the 2 frameworks only Export ERs are implemented, coming soon the Import implementation too

# RunERReportsByCode

This solution includes a generic small "framework" to run new ER from code easily and consistetly without worrying about the logic.

![image](https://github.com/FernitudelaDev/RunERReportsByCode/assets/143327172/b7c45a3e-40fc-4572-a74e-282a48b94b20)


It includes the logic to add some fields and UI behaviour to the ERSolutionTable, and 3 abstract classes that include all the logic and that you will have to extend (inherit) to create new ER report execution processes, that you will be able to call from a menu item in your child controller. 

In my youtube video: https://youtu.be/7LsKVV62jjw  and my blog post: http://fernitudela.dev/?p=1090 You will find a further explanation of how the solution works, as well as a step by step example of how to implement it.

In the solution you will also find a Sample implementation to help you with an example. The sample implementation includes the following objects:

![image](https://github.com/FernitudelaDev/RunERReportsByCode/assets/143327172/fc1a7cfc-0224-4b07-8b17-7d83839868c2)

# Service to run ERs from anywhere

As we presented in the 2024 Dynamics minds session: https://youtu.be/Fa-5-jKMV8k, 
here you are also the services to dynamically run ERs from outside (power platform or wherever you want):

![image](https://github.com/FernitudelaDev/RunERReportsByCode/assets/143327172/1bcac212-2519-4513-9581-13556036d87a)


It also includes the implementation of SalesOrderConfirmation Business docs, as an example of how you would need to do it for other BD. Hopefully we will be developing and uploading the rest of the common DP based reports soon.

PS: As a note aside, for the provided example of consuming the Sales Order Confirmation implementation, this additional setup in the ER form is needed:
![image](https://github.com/FernitudelaDev/RunERReportsByCode/assets/143327172/573a9b6a-bfb4-4d38-ab54-a2993b3c9d2b)


If you want to see the calls used in the Dyn minds demo, you can find the postman collection too in this repository.

Thank you!
