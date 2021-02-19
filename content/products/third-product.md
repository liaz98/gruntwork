+++
title = "Gruntwork Landing Zone for AWS"
description = "Streamline the way you create, configure, and secure AWS accounts."
date = 2020-06-30
+++
# A Terraform-native approach to AWS Landing Zone

A "Landing Zone" is a tool for quickly creating new AWS accounts, configuring AWS accounts with a standard security baseline, and defining a best-practices multi-account setup. Gruntwork Landing Zone helps you achieve all these goals using Terraform, allowing you to create and manage AWS accounts as code.”

# Create a Multi-Account AWS Structure

Gruntwork Landing Zone gives you the ingredients to create a best-practices multi-account structure using AWS Organizations, all based on official AWS recommendations.

# Quickly create new AWS accounts

Gruntwork Landing Zone includes an opinionated way to create a new AWS account as part of your AWS Organization using just three lines of code, plusa Terraform apply.

# Apply a best-practices security baseline to each AWS account

We define security baselines for the "root", "security", and "app" AWS accounts that include best-practices configurations for AWS CloudTrail, AWS Config, AWS Config rules, AWS IAM user password policies, cross-account access, Amazon GuardDuty, and more.

# 100% Terraform-native

Manage your accounts and security baselines as Terraform code. Update to the latest Gruntwork Landing Zone baselines or make AWS Organization changes such as setting AWS Config Rules with simple changes to Terraform code.

# Customize your AWS account baseline

Extend or customize your AWS account baselines by adding or removing any set of services you want directly in the Terraform code.

# Automate account creation

Because Gruntwork Landing Zone is 100% Terraform-native, you can create new accounts as part of any pipeline that runs Terraform code. For a production-ready example, see Gruntwork Pipelines.

# Available off the shelf

Gruntwork Landing Zone is pre-written, commercially supported, production-grade code that is available right now. No consulting engagement needed.

# Docs

See our guide How to configure a production-grade AWS account structure using Gruntwork AWS Landing Zone for step-by-step instructions on how to setup your Terraform AWS Landing Zone.

# Pricing

Gruntwork AWS Landing Zone is included as part of the Gruntwork Subscription. If you have questions about how it works or would like to see a demo, contact our sales team.
