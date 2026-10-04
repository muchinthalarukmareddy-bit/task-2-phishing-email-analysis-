# Phishing Email Analysis Report

## 1. Objective

The objective of this task is to identify phishing characteristics
in a suspicious email sample.

## 2. Email Details

Sender:
PayPal Security <security@paypa1-security.example>

Subject:
URGENT! Your account will be suspended

## 3. Phishing Indicators

### 3.1 Suspicious Sender Address

The sender uses a suspicious domain that resembles a legitimate
organization. The domain uses "paypa1" instead of "paypal".

### 3.2 Urgent and Threatening Language

The email states that the account will be permanently suspended
within 24 hours. This creates urgency and pressures the recipient
to act immediately.

### 3.3 Suspicious URL

The email contains:

http://paypa1-security.example/verify

The domain appears suspicious and does not match the expected
official organization domain.

### 3.4 Request for Sensitive Information

The email asks for the username, password and card information.
This is a major warning sign.

### 3.5 Spelling and Grammar

No major spelling errors were observed in the sample.
However, correct grammar does not prove that an email is legitimate.

### 3.6 Social Engineering

The email uses fear, urgency and the threat of account suspension
to encourage the recipient to act quickly.

## 4. Email Header Analysis

Actual email header information should be analyzed using a
header-analysis tool.

The following information should be checked:

- From
- Reply-To
- Received
- Message-ID
- SPF
- DKIM
- DMARC

No header authentication results are claimed here because the
sample email is a text file rather than a real email with
technical headers.

## 5. Conclusion

The sample contains several characteristics associated with
phishing, including a suspicious sender address, urgent language,
a suspicious URL and a request for sensitive information.

Users should verify suspicious messages independently and should
not click suspicious links or provide sensitive information.

## 6. Recommended Actions

- Do not click suspicious links.
- Do not open unknown attachments.
- Do not provide passwords or financial information.
- Verify the sender through an official communication channel.
- Report suspected phishing emails.
