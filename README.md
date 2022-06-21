# Elasticity-Labs-2
## Labs on Amazon Cloud Watch A

In this lab, we will view Amazon CloudWatch Automatic Dashboards

Amazon CloudWatch Automatic Dashboards allow you to easily monitor all AWS Resources, and is quick to get started. Explore account and resource-based view of metrics and alarms, and easily drill-down to understand the root cause of performance issues.

1. Open the Amazon CloudWatch console at https://console.aws.amazon.com/cloudwatch/ and select your region from the top menu bar.

2. If you are logging into a brand new AWS account, you will see the default Cloudwatch console such as this:

      <img width="552" alt="Cloudwatch 1" src="https://user-images.githubusercontent.com/103466963/174783146-4b3bada4-b33c-41ef-8072-435cd98d9291.png">

        You will need to deploy something into your account to see a Cloudwatch automatic dashboard.

3. Once you have services deployed into your AWS account, Cloudwatch will automatically populate the Overview tab with various metrics such as this:

      <img width="570" alt="cloudwatch 2" src="https://user-images.githubusercontent.com/103466963/174783628-56d87c12-fa9d-45cf-8796-2c45f02135cb.png">

4. The upper left shows a list of AWS services you use in your account, along with the state of alarms in those services. In this example, it is showing that we have an EC2 instance in use and it is marked as OK.

     <img width="570" alt="cloudwatch 3" src="https://user-images.githubusercontent.com/103466963/174784058-6fb317a6-a26b-4991-a272-1b578d041e57.png">

5. The upper right shows alarms in your account, which will contain up to four alarms that are in the ALARM state or it will show those that most recently changed state.

     <img width="570" alt="cloudwatch 4" src="https://user-images.githubusercontent.com/103466963/174784394-9cb8978c-e78f-448b-bb42-a6d64f9934a1.png">

These upper areas enable you to assess the health of your AWS services, by seeing the alarm states in every service and the alarms that most recently changed state. This helps you monitor and quickly diagnose issues.

6. Below these areas is spot for a custom default dashboard that you can create that is named CloudWatch-Default This is a convenient way for you to add metrics about your own custom services or applications to the overview page, or to bring forward additional key metrics from AWS services that you most want to monitor. In this example, we do not have a custom default dashboard created.

     <img width="570" alt="cloudwatch 5" src="https://user-images.githubusercontent.com/103466963/174784866-19c29907-7ff6-49cb-856d-b1d66a74121e.png">

. If you wish, you can click the “Create a new CloudWatch-Default dashboard” to generate a new dashboard and see it displayed in the overview screen.

7. If you use six or more AWS services, below the default dashboard is a link to the automatic cross-service dashboard. The cross-service dashboard automatically displays key metrics from every AWS service you use without requiring you to choose what metrics to monitor or create custom dashboards. You can also use it to drill down to any AWS service and see even more key metrics for that service.

     <img width="570" alt="cloudwatch 6" src="https://user-images.githubusercontent.com/103466963/174785362-dee3c102-c49e-4da8-a900-08b7b96d5134.png">
     
    In this example, we see both EC2 metrics as well as EBS volume metrics for the test machines that were created.

Remove the dashboard you created
The AWS free tier allows for 3 Dashboards for up to 50 metrics per month for free, but to ensure you are not charged for the dashboard, you should remove it if you created one in the previous step.








