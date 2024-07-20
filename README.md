# Terraform Elastic Beanstalk Application Deployment

## Overview

This beginner-friendly project demonstrates how to create an Elastic Beanstalk application using Terraform. It guides you through setting up Terraform, defining an Elastic Beanstalk application and environment, and managing these resources efficiently. Please be mindful of AWS costs associated with the resources created.

## Prerequisites

1. **Terraform Installation**

   Install Terraform on your local machine by following the official guide by HashiCorp:
   - [Install Terraform using CLI](https://learn.hashicorp.com/tutorials/terraform/install-cli)
   - [Download Terraform](https://www.terraform.io/downloads.html)

2. **Visual Studio Code Installation**

   Download and install Visual Studio Code by following this guide:
   - [Download Visual Studio Code](https://code.visualstudio.com/download)

## Task Details

1. **Sign in to AWS Management Console**

   - Access the AWS Management Console at [AWS Console](https://aws.amazon.com/console/).

2. **Setup Visual Studio Code**

   - Open Visual Studio Code and configure it for your Terraform project.

3. **Create a `variables.tf` File**

   - Define your variables in a `variables.tf` file.

4. **Create an Elastic Beanstalk Application**

   - Define the Elastic Beanstalk application in the `main.tf` file.

5. **Create an Elastic Beanstalk Environment**

   - Define the Elastic Beanstalk environment in the `main.tf` file.

6. **Create an `output.tf` File**

   - Specify the output variables in an `output.tf` file to obtain information about the deployed resources.

7. **Confirm Terraform Installation**

   - Verify the installation by checking the version:
     ```bash
     terraform version
     ```

8. **Apply Terraform Configurations**

   - Execute the Terraform commands to apply the configurations:
     ```bash
     terraform init
     terraform apply
     ```

9. **Check AWS Resources**

   - Verify the created Elastic Beanstalk application and environment in the AWS Management Console.


10. **Delete AWS Resources**

   - Remove the resources by executing:
     ```bash
     terraform destroy
     ```

## Cost Considerations

Be aware that creating and running AWS resources may incur costs. Review and understand the pricing for the Elastic Beanstalk and other AWS resources you are using. Always delete resources when they are no longer needed to avoid unnecessary charges.

## Documentation

- **Terraform Documentation:** [Terraform Official Documentation](https://www.terraform.io/docs)
- **AWS Documentation:** [AWS Official Documentation](https://docs.aws.amazon.com/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Notes

- Ensure you follow best practices for managing AWS resources and Terraform configurations.
- For additional help, refer to the official [Terraform Documentation](https://www.terraform.io/docs) and [AWS Documentation](https://docs.aws.amazon.com/), or seek support from the community.
