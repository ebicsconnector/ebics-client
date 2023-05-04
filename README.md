# EBICS Client Micro-Service

The EBICS Client Micro-Service is a lightweight and easy-to-integrate implementation of version 2.4.2 of the EBICS (Electronic Banking Internet Communication Standard) protocol for clients looking to quickly and efficiently integrate EBICS into their system architecture.

## Table of Contents

- [Features and Benefits](#features-and-benefits)
- [How to Obtain the Micro-Service](#how-to-obtain-the-micro-service)
- [Support and Maintenance](#support-and-maintenance)
- [Contribute and Share](#contribute-and-share)

## Features and Benefits

Our EBICS Client Micro-Service supports the following EBICS commands:

- HEV: Download the list of EBICS versions supported by the EBICS server
- INI: Transfer the public bank-technical subscriber certificate to the EBICS server.
- HIA: Transfer the subscriber's public identification and authentication certificate and the subscriber's public encryption certificate to the EBICS server.
- HPB: Download the EBICS server's public keys.
- FUL: Upload a file to the EBICS server.
- FDL: Download a file from the EBICS server.
- HCS: Issue new keys for the bank-technical subscriber (signature certificate) as well as for the identification/authentication and encryption.
- HCA: Issue the subscriber's new identification/authentication key as well as the subscriber's new encryption key.
- PUB: Issue only the new bank-technical subscriber key (signature certificate).
- SPR: Suspend a given subscriber

The main benefits of our implementation include:

- Ease of integration: Designed as a micro-service, it can be easily integrated into various system architectures.
- Flexibility: Compatible with multiple programming languages and platforms.
- Security: Complies with the security and cryptography standards of the EBICS protocol.

## How to Obtain the Micro-Service

To obtain a copy of the EBICS Client Micro-Service, please [contact our sales team](mailto:contact@ebics-connector.com). We will provide you with a binary version of the micro-service along with installation and usage instructions.

## Support and Maintenance

If you need assistance using or integrating the EBICS Client Micro-Service, please [contact our support team](mailto:support@ebics-connector.com). We also offer maintenance and enhancement services upon request.

## Contribute and Share

If you find our EBICS Client Micro-Service useful, we encourage you to share it with your professional network, on social media, and on specialized forums. Incoming links to our GitHub repository can help improve its visibility and assist others in discovering this project.

Do not hesitate to send us your feedback, improvement suggestions, and feature requests. We are always interested in the opinions of our user community to continue improving our micro-service.
