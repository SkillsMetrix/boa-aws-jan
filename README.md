1) Create VPC and More to create ( Subnets,IG,Route Tables) (amar-boa-vpc)

2) Target Group ( amar-boa-tg)

3) create load balancer (amar-boa-lb) :80  SG (amar-boa-sg-http)

4) assign LB to TG

5) create ASG (amar-boa-asg)

6) create launch template and define the template of Ec2 machines (amar-boa-template)

7) create SG for template (amar-boa-ec2-sg)


---------------------

Step Function ( conditional flow diagram) -> invoke lambda

ecommerce 	->purchase -> lambda (serverless fun) process the task when trige
		-> Refund -> Lambda
		-> accounts
--


AppSync (GraphQl)Replacing REST -> exposing endpoints
