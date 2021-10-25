# Devloping countries Healthcare Claims Automation with DAML 

## Overview

This application simulates processing a healthcare claim in developing countries like India, bangladesh and others.. Healthcare in these countries is financed through a complex mixture of public subsidies, mandatory personal savings and optional, integrated commercial health insurance. This complexity has resulted in uneven and manual workflows in order to determine the precise amounts owed by IRDAI (the public subsidy), the IP Insurer (the commercial healthplan), and the Patient. The application demonstates a straight-thru, real-time process for multi-lateral claims process, starting with the scheduling of a hospital procedure, including the generation of a "Letter of Guarantee" from the commercial insurer, checking in the patient on the date of the appointment, checking out the patient after service delivery, generation of the claim, and finally, payment for the procedure by all parties. 

## Getting Started

### Installing

**Disclaimer:** This reference application is intended to demonstrate the capabilities of the DAML. You are recommended to consider other non-functional aspects, like security, resiliency, recoverability, etc prior to production use.

#### Prerequisites

Be sure you have the following installed.
- [DAML SDK](https://docs.daml.com/)
- Java 8 or higher

### Starting the App

1. Build, then start the DAML Sandbox and Navigator. Type:
    ```shell
    daml start
    ```
    The navigator will automatically open in new browser tab at http://localhost:7500.

### Stopping the App

1. Stop the Sandbox and the Navigator by pressing **Ctrl+C** in the DAML assistant.


IRDAI: https://www.irdai.gov.in/

