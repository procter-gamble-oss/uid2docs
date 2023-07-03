---
title: Implementing Sharing
description: Learn about how to implement sharing.
hide_table_of_contents: false
sidebar_position: 03
---

# Implementing Sharing

<!-- This page provides information about sharing UID2 information: what sharing means, who you can share with, the benefits of sharing, how to set up and manage your sharing permissions, and lots more! Use sharing permissions to expand your reach and help your business to prosper. -->

<!-- It includes the following:

- [UID2 Sharing Background](#uid2-sharing-background)
  - [UID2 Token Pass-Through](#uid2-token-pass-through)
- [UID2 Sharing Workflow](#uid2-sharing-workflow)
  - [One-Time Setup Steps](#one-time-setup-steps)
  - [Action Steps](#action-steps)
- [UID2 Sharing: Implementation Guidelines](#uid2-sharing-implementation-guidelines)
- [UID2 Portal Sharing Permissions](#uid2-portal-sharing-permissions)
  - [Steps for Granting Sharing Permission](#steps-for-granting-sharing-permission) -->

Setting up UID2 sharing requires some steps by each participant:
- The sender, who sends encrypted UID2 tokens to an authorized sharing participant.
- The receiver, who receives the encrypted UID2 tokens and decrypts them.

## Steps to Implement Sharing

The following steps are for all sharing participants&#8212;senders and receivers.

1. Decide which SDK or integration tool to use, from the following options, and review the examples in the applicable sharing documentation to see what the sharing code might look like.

   | SDK/Integration Tool | Link to Sharing Section |
   | :--- | :--- | 
   | C# / .NET | [UID2 SDK for C# / .NET: Usage for UID2 Sharers](../sdks/uid2-sdk-ref-csharp-dotnet.md#usage-for-uid2-sharers) |
   | C++ | [UID2 SDK for C++: Usage for UID2 Sharers](../sdks/uid2-sdk-ref-cplusplus.md#usage-for-uid2-sharers) |
   | Java | [UID2 SDK for Java: Usage for UID2 Sharers](../sdks/uid2-sdk-ref-java.md#usage-for-uid2-sharers) |
   | Python | [UID2 SDK for Python: Usage for UID2 Sharers](../sdks/uid2-sdk-ref-python.md#usage-for-uid2-sharers) |
<!--    Snowflake TBD GWH TO LINK TO SNOWFLAKE SHARING SECTION../guides/snowflake_integration.md -->

2. Integrate the SDK into your code to implement each step, depending on whether your role is sender or receiver. To see code examples for the language you're using, follow the link in the table provided in Step 1.
   1. Both senders and receivers: define the UID2 client.
   
   2. Both senders and receivers: define the token refresh schedule. Recommended refresh interval is hourly.

   3. Senders, set up encryption.

   4. Receivers, set up decryption.