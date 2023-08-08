# Setting Up Blockchain Node Engine for Ethereum Validator on GCP

## Prerequisites

- **Google Cloud Account:** Ensure you have a Google Cloud account with active billing.
- **Google Cloud Project:** Create a new Google Cloud project. Note down the project ID and project number, adhering to naming guidelines.
- **Permissions:** The individual provisioning Blockchain Node Engine requires specific IAM permissions:
  - **Viewer Role:** Read access to all Blockchain Node Engine resources.
  - **Admin Role:** Full access to all Blockchain Node Engine resources and API key management.

## Step 1: Enable APIs

1. Open the Google Cloud Console.
2. Navigate to **APIs & Services > Dashboard**.
3. Click on **+ ENABLE APIS AND SERVICES**.
4. Search for "Blockchain Node Engine" and enable the following APIs:
   - Blockchain Node Engine API
   - Compute Engine API
   - Service Usage API

## Step 2: Configure API Keys

1. Go to **APIs & Services > Credentials** in the Google Cloud Console.
2. Click on **+ CREATE CREDENTIALS > API key**.
3. Securely store the generated API key for later use.

## Step 3: Deploy Ethereum Validator Node

1. Determine the blockchain network (mainnet or testnet) and consensus client.
2. Deploy a blockchain node using Blockchain Node Engine with configurations, using the generated API key.

## Step 4: Monitor and Manage

1. Monitor validator status through Blockchain Node Engine.
2. Stay updated with Ethereum and Blockchain Node Engine updates.
3. Manage validator using IAM roles, granting access if needed.

## Step 5: Security and Best Practices

1. Implement firewall rules for security.
2. Keep wallet and keys secure and backed up.
3. Apply security patches promptly.

## Step 6: Staking and Validation

1. Stake ETH to become a validator.
2. Monitor performance and rewards.
3. Engage with Ethereum community for updates.

# Blockchain Node Engine Node Upgrades and Maintenance

## Node Maintenance

- Upgrades of blockchain client software.
- Updates to Blockchain Node Engine business logic (features, bug fixes, maintenance).
- GKE cluster software and infrastructure updates.

## Node Downtime

- Upgrades can cause downtime from a minute to up to 40 minutes.
- Multiple nodes across locations can distribute load and minimize downtime.

## Maintenance Windows

- Regular update windows (1st Monday of each month).
- Locations: us-central1 (9-10AM PST), europe-west1 (10-11AM PST), asia-east1 (11AM-12PM PST).
- Notice provided; unplanned urgent updates possible.

# Enabling Blockchain Node Engine API

To enable the Blockchain Node Engine API:

1. Go to the Google Cloud Console.
2. Navigate to the **Blockchain Node Engine API** page.
3. Click **Enable**. Wait for the process to complete.

This comprehensive guide covers setting up Blockchain Node Engine for an Ethereum validator, managing node upgrades and maintenance, and enabling the Blockchain Node Engine API on Google Cloud Platform. Refer to official documentation for detailed instructions and updates specific to your setup.
