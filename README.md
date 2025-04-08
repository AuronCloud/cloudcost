# Cloud Cost

[![PyPI version](https://img.shields.io/pypi/v/cloudcost.svg)](https://pypi.org/project/cloudcost/)
[![Python Versions](https://img.shields.io/pypi/pyversions/cloudcost.svg)](https://pypi.org/project/cloudcost/)

## 🌟 Overview
Cloud Cost is an advanced, easy-to-use Python utility designed to help organizations and cloud administrators optimize and manage Cloud infrastructure costs effectively. By providing deep insights and actionable recommendations, this tool empowers teams to reduce cloud spending without compromising performance.

## ✨ Features

### 🔍 Comprehensive Cost Analysis

- Detailed Breakdowns: Granular analysis of AWS resource expenditures
- Real-time Tracking: Monitor cost trends and anomalies
- Resource Insights: Identify underutilized or idle resources

### 💡 Intelligent Recommendations

- Automated Suggestions: Smart cost-saving strategies
- Optimization Guidance: Recommendations for EC2 instances, storage, and networking, etc...

### 🛡️ Easy Integration

- Simple CLI: Straightforward command-line interface
- AWS Compatibility: Seamless integration with existing AWS environments
- Multi-service Support: Analyze various AWS service resources

### 🚀 Installation

Install Cloud Cost using pip:
```shell
pip install cloudcost
```

### 🔧 Quick Start
Make sure you have AWS profile configured on CLI

#### Configure AWS credentials
```
$ aws configure
AWS Access Key ID [None]: <ENTER_YOUR_KEY_ID>
AWS Secret Access Key [None]: <ENTER_YOU_SECRET_ID>
Default region name [None]: <ENTER_REGION>
```

Checkout official documentation for [configuration](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart.html#getting-started-quickstart-new-command)

### Run cost analysis
```
usage: cloudcost [-h] [--version] [--profile PROFILE] [--region REGION]

options:
  -h, --help         show this help message and exit
  --version          Show the version
  --profile PROFILE  AWS profile to use
  --region REGION    AWS region to analyze
```

For example,
```shell
cloudcost --profile default --region us-east-1
```
It will analyse the existing usage and if the tool detects the cost saving opportunity, it will show you specific information and recommendations. 


### 💰 Key Benefits

- Reduce cloud infrastructure costs by up to 67%
- Gain transparent insights into cloud spending
- Make data-driven resource allocation decisions
- Minimal configuration required

### 📋 System Requirements

- Python: 3.9+
- AWS Credentials: Read-only access recommended
- Supported Platforms: Linux, macOS, Windows

Project Link: [GitHub Repository](https://github.com/AuronCloud/cloudcost)
