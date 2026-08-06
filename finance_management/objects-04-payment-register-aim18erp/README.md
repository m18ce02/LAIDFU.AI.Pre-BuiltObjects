## Version and Changelog
-**v1.0.0** (2026-08-04): Initial version, payment register AI assistant that enables multilingual interaction and automated payment entry, with automatic ID resolution and data validation from the system.

## Feature Overview
- This Object demonstrates a Payment Register AI Assistant, supporting Simplified Chinese, Traditional Chinese, and English interactions. Users can create payment entries through 【AI Square】enabling faster and more automated payment processing.
Core Features:
1. **Multi-language interaction**: supports Simplifed Chinese, Traditional Chinese and English use cases.
2. **Intelligent data extraction**: automatically extracts payment details from conversational input, guiding the user to complete any missing required fields.
3. **Intent regcognition and record generation**: the 【Chat-to-Action Robot】automatically identifies the payment creation intent, and calls the module 【AI Chat-to-Payment Register Data Container】to generate an entry for submission and approval.
4. **Automated process validation**: automatic vendor/supplier ID confirmation and profile lookup, required field completeness checks, and rule-based validation.
5. **ERP integration**: generates and syncs the Payment Register entry into aiM18 across the relevant subtables, enabling seamless integration.
6. **Confirmation and notification**: sends a confirmation message once the entry is created, so users can verify the results immediately.

## Product Feature Requirements
To use this Object, you must at minimum purchase aiM18 and install the folling module features:
- AI Builder (智筑引擎LAIDFU) 
- AI Square (万达宝智能⼴场) 
- Chat-to-Action Robot (聊天⾏动机器⼈)
- Supply Chain Management (供应链管理)
- Financial Management (财务管理)

## Installation and Configuration
1. From this folder, download the installation package "install_file.zip".
2. Extract the zip file to a local folder.
3. Read and follow the extracted "Objects_install_guide_payment_register_v1.0.0.pdf" to complete configuration.
4. Import the Object files into aiM18, and verify the feature runs correctly.

## Precautions
### 1. Data backup
- If the target system already has a custom configuration (e.g. modified default parameters or added custom rules), it is strongly recommended to back up existing data before installation, to prevent accidental overwrite or configuration conflicts.
### 2. Version compatibility check
- Ensure the current aiM18 platform version matches this Object's minimum version requirement.
- Detailed version requirements can be found in "Objects_install_guide_payment_register_v1.0.0.pdf" in this folder.
### 3. Environment verification
- Before installation, check that the system environment meets this Object's dependency requirements (e.g. specific AI model version, specific BE requirements).
### 4. Configuration conflict prevention
- If a similar Payment Register Object already exists in the system, confirm before installing whether it will overwrite the existing configuration.
- It is recommended to deploy in a test environment first, and apply to production only after confirming there are no conflicts.