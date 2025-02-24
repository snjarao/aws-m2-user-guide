# Deploy a AWS Mainframe Modernization application<a name="applications-m2-deploy"></a>

Use the AWS Mainframe Modernization console  to deploy q AWS Mainframe Modernization application\.

These instructions assume that you have completed the steps in [Setting up AWS Mainframe Modernization](setting-up.md)\.

## Deploy an application<a name="applications-m2-deploy-console"></a>

After you create a AWS Mainframe Modernization application, you must deploy it to a runtime environment in order to run it\. When you deploy an application, you actually deploy a specific version of the application, which has its own application definition\. To redeploy a different application version, you must delete the existing application deployment from the runtime environment first\.

**To deploy an application**

1. Open the AWS Mainframe Modernization console at [https://console\.aws\.amazon\.com/m2/](https://console.aws.amazon.com/m2/)\.

1. In the region selector, choose the AWS Region where you want to create the application\.

1. On the **Applications** page, choose the application you want to deploy\.

1. Choose **Actions**, then choose **Deploy application**\.

1. In **Environments**, choose a runtime environment where you want your application to run\.

1. Choose **Deploy**\.