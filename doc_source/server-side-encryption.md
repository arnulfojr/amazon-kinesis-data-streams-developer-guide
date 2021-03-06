# Data Protection in Amazon Kinesis Data Streams<a name="server-side-encryption"></a>

Server\-side encryption using AWS Key Management Service \(AWS KMS\) keys makes it easy for you to meet strict data management requirements by encrypting your data at rest within Amazon Kinesis Data Streams\.

**Note**  
If you require FIPS 140\-2 validated cryptographic modules when accessing AWS through a command line interface or an API, use a FIPS endpoint\. For more information about the available FIPS endpoints, see [Federal Information Processing Standard \(FIPS\) 140\-2](http://aws.amazon.com/compliance/fips/)\.

**Topics**
+ [What Is Server\-Side Encryption for Kinesis Data Streams?](what-is-sse.md)
+ [Costs, Regions, and Performance Considerations](costs-performance.md)
+ [How Do I Get Started with Server\-Side Encryption?](getting-started-with-sse.md)
+ [Creating and Using User\-Generated KMS Master Keys](creating-using-sse-master-keys.md)
+ [Permissions to Use User\-Generated KMS Master Keys](permissions-user-key-KMS.md)
+ [Verifying and Troubleshooting KMS Key Permissions](sse-troubleshooting.md)
+ [Using Amazon Kinesis Data Streams with Interface VPC Endpoints](vpc.md)