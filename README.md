# AI Health Risk & Blood Report Analyzer

This is capstone project of the Hacktiv8 x IBM Skillsbuild University Education - Healthcare program 

AI-powered healthcare assistant built using Langflow and Gemini to analyze Complete Blood Count (CBC) reports from PDF files and provide patient-friendly health insights.

## Overview

This project helps users understand blood test results by automatically analyzing CBC reports and generating:

- Medical Summary
- Risk Level Classification
- Abnormal Indicator Detection
- Normal Range Comparison
- Patient-Friendly Explanation
- Health Risk Highlight
- Personalized Recommendation
- Medical Disclaimer

The system is designed to simplify medical report interpretation for non-medical users while avoiding definitive diagnosis.

## Features

### Clinical Blood Report Analysis
Upload CBC report in PDF format and receive structured healthcare analysis.

### Risk Level Classification
Categorizes results into:
- Low Risk
- Moderate Risk
- High Risk

### Abnormal Indicators Detection
Displays:
- Patient result
- Normal range
- Status (High/Low)
- Severity level
- Possible interpretation

### Patient-Friendly Explanation
Converts medical findings into simple language.

### Health Recommendation
Provides general healthcare suggestions based on report findings.

## Workflow

```text
Upload CBC Report PDF
          ↓
Read File
          ↓
Type Converter
          ↓
Prompt Engineering
          ↓
Gemini LLM Analysis
          ↓
Structured Healthcare Output
```

## Tech Stack

- Langflow
- Gemini 2.5 Flash Lite
- Prompt Engineering
- AI Agent Workflow

## Project Architecture

Input:
- CBC Blood Report PDF

Process:
- Extract report content
- Convert document into readable format
- Analyze abnormal indicators
- Compare with normal range
- Generate structured healthcare explanation

Output:
- Medical Summary
- Risk Level
- Abnormal Indicators Table
- Patient-Friendly Explanation
- Health Recommendation

## Disclaimer

This system is intended for educational purposes only and does not replace professional medical diagnosis or healthcare consultation.
