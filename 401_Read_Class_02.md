# Cloud Security Principles and Frameworks

*this is a summary of Massimo Re Ferre's web article titled "Compute Abstractions on AWS: A Visual Story"* 

[Here is a link to that article](https://aws.amazon.com/blogs/architecture/compute-abstractions-on-aws-a-visual-story/)

The author defines the compute domain as *"anything that has CPU and Memory capacity that allows you to run an arbitrary piece of code, written in a specific programming language."*

They then talk about the separation of duties in the cloud saying *"there are things that AWS will do and things that the consumer will do.  The perimeter of these responsibilities varies depending on the services you op to use."*  Marco mentioned in class a specific responsibility could be securing ports.  While Amazon is providing you the web service, it wouldn't be their responsibility to make sure the user sets up the service in a secure way.

The first image in the article splits the Consumer Space (managed by the customer) and the Provider space (managed by AWS).  In the Provider space you see the physical server, VM, container and function.  They note that "the higher you go in the abstraction levels, the more the cloud provider can add value and can offload the consumer from non-strategic activities."

The next part of the article talks about "The instance abstraction". Here an instance is a virtual machine. The first abstraction Amazon offered was in 2006, their Amazon Elastic Compute Cloud (Amazon EC2). 

The next abstraction is "The container abstraction".  Docker is an example of this.  A container is a "self-contained environment with soft boundaries that includes both your own application as well as the software dependencies to run it." 

Next is "The function abstraction". AWS Lambda is an example given.  It is an execution environment that allows an AWS customer to run a single function. A Lambda function can be triggered in another AWS service.

The "bare metal abstraction" is a service that offers low-level hardware for virtualized environments.  This is their most basic AWS service. 

And last they offer "The full container abstraction".  The service at this level is called AWS Fargate.  It's a production-grade service that provides "compute capacity to AWS containers control planes." This puts the data plane in the responsibility of the "Provider Space." 



