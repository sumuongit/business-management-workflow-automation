# Business Management & Workflow Automation Prototype

## Overview

A practical business management and workflow automation prototype designed around a construction business.

The solution uses Notion as a central workspace for sales CRM, construction project management, supplier management and financial records. n8n provides workflow automation for processing supplier invoices and integrating extracted information with Notion.

## Key Components

### 1. Sales CRM
- Contact and opportunity management
- Sales pipeline and follow-up tracking
- Sales activities and management dashboard

### 2. Construction Project Management
- Project lifecycle management
- Reusable project templates
- Task assignments, deadlines and progress tracking
- Materials, supplier and equipment hire management

### 3. Invoice Processing Automation
- Email-based invoice intake
- AI-assisted invoice data extraction
- Supplier and project validation
- Duplicate invoice detection
- Project cost record creation or updates in Notion

## Technology Stack

- Notion
- Notion API
- n8n
- Docker
- Google Gemini API
- REST API Integration
- Workflow Automation

## Architecture

Notion serves as the central business data workspace, while n8n handles the invoice-processing workflow and integration between incoming emails, AI-assisted extraction and Notion records.

## Testing

The prototype was tested using sample invoice data to verify data extraction, supplier and project matching, validation and Notion record creation or updates.

## Current Scope and Limitations

This is a prototype rather than a production deployment. Further work could include role-based access control, expanded notification and approval workflows, additional document-format support, and testing with real business data.

## Purpose

This project demonstrates practical experience in business process analysis, solution design, database relationships, API integration and workflow automation.
