The AWS SDK for Java provides a Java API for Amazon Web Services. Using the SDK, you can easily build Java applications that work with Amazon S3, Amazon EC2, Amazon SimpleDB, and more. We regularly add support for new services to the AWS SDK for Java.

The AWS SDK for Java API Reference represents the most recent version of the SDK. If you're using an earlier SDK version, you might want to access the SDK reference documentation that matches the version you're using.

The easiest way to build the documentation is using Apache's Maven build tool. Download and install Maven first if you don't already have it on your system, then use the following instructions to build the reference documentation.

To build reference documentation for an earlier SDK version:

Locate and select the SDK version that you're using on the releases page of the SDK repository on GitHub.

Choose either the zip (most platforms, including Windows) or tar.gz (Linux, macOS, or Unix) link to download the SDK to your computer.

Unpack the archive to a local directory.

On the command line, navigate to the directory where you unpacked the archive, and type the following.

mvn javadoc:javadoc
After building is complete, you'll find the generated HTML documentation in the aws-java-sdk/target/site/apidocs/ directory.

Amazon Web Services (AWS) is the market leader in IaaS (Infrastructure-as-a-Service) and PaaS (Platform-as-a-Service) for cloud ecosystems, which can be combined to create a scalable cloud application without worrying about delays related to infrastructure provisioning (compute, storage, and network) and management.

With AWS you can select the specific solutions you need, and only pay for exactly what you use, resulting in lower capital expenditure and faster time to value without sacrificing application performance or user experience.

Amazon offers many services for application development and analytics. Here are some key building blocks in the AWS environment and a brief description of how they are leveraged against your needs.

