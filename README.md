Created a service with AWS Lambda, S3, DynamoDb, SES, and Amazon Textract to ananlyse receipts, and to email it to the user required.

This project focuses on automating receipt processing using AWS services. Instead of manually handling receipts which can be time-consuming, error-prone, and difficult to scale—this system extracts structured data from receipts and stores it efficiently for record-keeping and auditing.

The architecture consists of:

Storage Layer: Amazon S3 stores receipt images and PDFs.

Processing Layer: Amazon Textract extracts text from receipts using AI-powered OCR.

Database Layer: DynamoDB stores the extracted data in a structured format.

Notification System: Amazon SES sends email alerts with receipt details.

Compute Layer: AWS Lambda automates the workflow by processing the receipts in real-time.



Services Used 🛠️
Amazon S3: Stores uploaded receipt images and PDFs. [Storage]

Amazon Textract: Extracts text and structured data from scanned receipts. [AI/ML]

Amazon DynamoDB: Stores extracted receipt data in a structured format. [Database]

Amazon SES: Sends email notifications with extracted receipt details. [Messaging]

AWS Lambda: Automates the processing workflow for real-time execution. [Compute]

IAM Roles & Policies: Ensures secure access between services. [Security]

<img width="1423" height="515" alt="Screenshot 2025-11-25 at 7 21 22 PM" src="https://github.com/user-attachments/assets/2541efb5-4ed1-4078-8896-2f26e8d9e012" />


<img width="1440" height="455" alt="Screenshot 2025-11-25 at 7 22 44 PM" src="https://github.com/user-attachments/assets/9f0c0c28-9753-40d2-84ee-e3cd1363ba15" />


<img width="1440" height="515" alt="Screenshot 2025-11-25 at 7 27 33 PM" src="https://github.com/user-attachments/assets/714a8351-45ae-4fe1-9e58-a5d5b32c7bf5" />


<img width="1425" height="508" alt="Screenshot 2025-11-25 at 7 27 47 PM" src="https://github.com/user-attachments/assets/5dd8235b-f0af-43ad-8fe5-8ed99d7bda14" />


<img width="1436" height="636" alt="Screenshot 2025-11-25 at 7 30 30 PM" src="https://github.com/user-attachments/assets/65db9be5-2ff7-44de-9d33-8541cdd64ad5" />


<img width="1433" height="742" alt="Screenshot 2025-11-25 at 7 31 59 PM" src="https://github.com/user-attachments/assets/ad04ee96-2974-4df1-90c7-d40dfffa0b88" />


<img width="1422" height="670" alt="Screenshot 2025-11-25 at 7 33 19 PM" src="https://github.com/user-attachments/assets/7bda8d45-2cb8-4844-9299-0e0472e465ea" />





