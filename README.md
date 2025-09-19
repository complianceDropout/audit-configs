# Office Portal Utilities

This repository contains miscellaneous utilities and configuration files 
for the **Office Portal** project.

## Overview

The Office Portal system provides internal access to reporting, timesheet management, and compliance auditing features.  

These utilities are primarily used for testing and prototyping purposes.  
*Do not use in production.*

## Configuration Example

For reference in this challenge, here’s some example pieces of the config:

sessionTimeout: 30

officePortal.internalAudit: enabled

twoFactorAuth: required


These values reflect how core services are toggled and secured during deployment.

## Contents

- `config.yaml` → Example configuration file with common security flags.  
- `README.md` → Project documentation.  

## Notes

This repo was quickly set up for demonstration and should be treated 
as experimental. Future versions will be merged into the main 
intranet services repository.
