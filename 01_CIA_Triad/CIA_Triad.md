# CIA Triad Documentation

## 1. Introduction

The CIA Triad is one of the basic concepts of cybersecurity. It consists of three main principles:

- Confidentiality
- Integrity
- Availability

These principles help protect information and systems from different types of security problems.

## 2. Confidentiality

Confidentiality means preventing unauthorized users from accessing information.

For example, in a university system, a student should be able to view his own grades and personal information, but he should not be able to see another student's private information.

Authentication and authorization can help protect confidentiality. Permissions can also be used to control access to files and information.

For example, in Linux:

- `r` = read
- `w` = write
- `x` = execute

A user should only receive the permissions that are necessary for their job. This is related to the principle of least privilege.

## 3. Integrity

Integrity means keeping data accurate and preventing unauthorized modification.

For example, if a student's grade is:

`Math = 60`

and an unauthorized user changes it to:

`Math = 90`

the integrity of the data has been compromised.

Authentication, authorization, permissions, hashing, and digital signatures can help protect data integrity.

## 4. Availability

Availability means that authorized users should be able to access a system or information when they need it.

For example, students should be able to access a university registration website when they need to register for courses.

A DDoS attack can affect availability by sending a large amount of traffic to a server and making it difficult for legitimate users to access the service.

Backups, monitoring, redundant systems, and DDoS protection are some ways to improve availability.

## 5. Authentication and Authorization

Authentication and authorization are related but they have different purposes.

Authentication answers:

"Who are you?"

When a user logs in with a username and password, the server verifies the user's identity.

After successful authentication, the server may provide an access token. The browser can then send this token with future requests.

Authorization answers:

"What are you allowed to do?"

For example, the server may identify a user as an Editor and allow the user to access editing functions while blocking access to administrator functions.

A simple flow is:

User
  ↓
Web Browser
  ↓
Login
  ↓
Server
  ↓
Authentication
  ↓
Access Token
  ↓
Request + Token
  ↓
Server
  ↓
Authorization
  ↓
Allow or Deny

This is important for both Confidentiality and Integrity, because users should only be able to access and modify information they are authorized to use.

## 6. How the CIA Triad Works Together

The three principles work together to provide better security.

For example, consider an online banking system:

- Confidentiality: Unauthorized users should not be able to view a customer's account information.
- Integrity: Unauthorized users should not be able to modify the customer's balance or transactions.
- Availability: The customer should be able to access the banking service when needed.

A secure system should consider all three principles rather than focusing on only one.

## 7. Conclusion

The CIA Triad provides a simple way to understand the main goals of information security.

Confidentiality protects information from unauthorized access.

Integrity protects information from unauthorized changes.

Availability makes sure that authorized users can access systems and information when needed.

Authentication, authorization, permissions, and other security mechanisms can be used to support these principles and protect computer systems and networks.
