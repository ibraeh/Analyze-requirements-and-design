# Analyze-requirements-and-design
AWS Generative AI Developer - Analyze Requirements and Design Generative AI Solutions


## Title 
Building an AI-Powered Insurance Claim Processor with Amazon Bedrock

## 🎯 Scenario

An insurance company wants to automate processing of claim documents to reduce manual effort and improve consistency.

## 💼 Task

To Build a proof-of-concept document processing solution that extracts information from insurance claim documents and generates summaries using Amazon Bedrock.

## 🏗️ Architecture
```
User uploads claim document
        ↓
Amazon S3 (claim-documents bucket)
        ↓
AWS Lambda (Document Processor)
        ↓
Amazon Bedrock (Foundation Models)
        ↓
Policy Knowledge Base (RAG - optional S3 / OpenSearch)
        ↓
Claim Summary + Extracted JSON
        ↓
Store result in S3 or DynamoDB
```
view [architecture.svg](https://github.com/ibraeh/Analyze-requirements-and-design/blob/main/architecture.svg)

## 📁 Project Structure




