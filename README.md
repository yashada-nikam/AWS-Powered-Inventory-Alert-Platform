# AWS-Powered-Inventory-Alert-Platform

This project demonstrates a serverless solution to monitor inventory levels in real-time and send automated alerts when stock levels fall below a predefined threshold. It uses AWS services such as DynamoDB, Lambda, and SNS for seamless functionality.

---

## **Features**
- Real-time inventory monitoring
- Threshold-based low stock alerts
- Serverless architecture using AWS Lambda
- Scalable and cost-effective solution

---

## **Tech Stack**
- **AWS Services**: DynamoDB, Lambda, SNS, S3, API Gateway
- **Programming Language**: Python (Boto3)
- **Infrastructure as Code (IaC)**: AWS CloudFormation

---

## **Project Architecture**
1. **DynamoDB**: Stores inventory data with stock levels.
2. **Lambda Functions**: Triggered by inventory changes to check stock thresholds.
3. **SNS**: Sends email/SMS notifications for low stock alerts.
4. **S3**: Hosts static resources or logs (optional).
5. **API Gateway**: Facilitates external integration for adding/updating inventory.

---

## **How to Use**
1. Add inventory records to DynamoDB with attributes like `product_id`, `product_name`, and `stock_level`.
2. Lambda automatically evaluates stock levels and triggers SNS for low-stock alerts.
3. Subscribe to the SNS topic to receive alerts via email or SMS.

---

## **Future Improvements**
- Integrate with third-party inventory systems.
- Add support for multi-region inventory tracking.
- Implement predictive analytics for inventory forecasting.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.
