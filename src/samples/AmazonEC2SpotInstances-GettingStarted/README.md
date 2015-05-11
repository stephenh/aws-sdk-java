# Amazon EC2 Spot Instance Getting Started Sample

This is a sample that demonstrates how to set up requests for Spot Instances, how to determine when they have completed, and how to clean up afterwards.

## Prerequisites

*   You must have a valid Amazon Web Services developer account.
*   Requires the AWS SDK for Java. For more information on the AWS SDK for Java, see [http://aws.amazon.com/sdkforjava](http://aws.amazon.com/sdkforjava).
*   You must be signed up to use Amazon EC2. For more information on Amazon EC2, see [http://aws.amazon.com/EC2](http://aws.amazon.com/ec2).

## Running the Sample

The basic steps for running the Amazon EC2 Spot Instance Getting Started sample are:

1.  Open the `AwsCredentials.properties` in the sample folder.

2.  Locate the following section and fill in your Access Key ID and Secret Access Key:  

    ```
    # Fill in your AWS Access Key ID and Secret Access Key  
    # http://aws.amazon.com/security-credentials
    accessKey =  
    secretKey =
    ```

3.  Save the file.

4.  Copy the file to the getting_started subdirectory, the output directory for build.

5.  Run the `CreateSecurityGroupApp.java` file, located in the same directory as the properties file. To use ant to run the file, type "ant CreateSecurityGroupApp"

6.  Run the `GettingStartedApp.java` file, located in the same directory as the properties file. The sample prints information to the standard output. To use ant to run the file, type "ant GettingStartedApp"

**NOTE:** The sample also includes an Ant build.xml file to run the sample.

See the [AWS Developer Guide for Java](http://docs.amazonwebservices.com/AWSSdkDocsJava/latest/DeveloperGuide/tutorial-spot-instances-java.html) for more information about running this sample.