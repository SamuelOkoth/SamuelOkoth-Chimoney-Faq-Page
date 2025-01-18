# # Chimoney Developer Toolkit - Frequently Asked Questions (FAQs)

## Introduction
Welcome to the Chimoney Developer Toolkit FAQ page. This resource is designed to help developers quickly find answers to common questions, troubleshoot issues, and adopt best practices for integrating and using Chimoney’s API.

---

## General Questions

### What is Chimoney API?
Chimoney API is a versatile solution that enables businesses and developers to facilitate global payouts easily and securely. With Chimoney, you can send payments in multiple currencies, ensuring compliance and efficiency.

### How do I get started with Chimoney API?
1. Sign up for a Chimoney account on [Chimoney.io](https://chimoney.io).
2. Access the API documentation at [Chimoney API Docs](https://chimoney.io/docs).
3. Generate an API key from your account dashboard.
4. Start integrating Chimoney API into your application.

### Where can I find the API documentation?
The official API documentation is available at [Chimoney API Documentation](https://chimoney.io/docs), where you’ll find detailed guides, examples, and references.

---

## Authentication and Security

### How to obtain an API key?
1. Log in to your Chimoney account.
2. Navigate to the **API Keys** section in your dashboard.
3. Click on **Generate API Key** and save it securely.

### How to manage and rotate API keys?
- **Managing Keys:** Use your dashboard to view and deactivate old keys.
- **Rotating Keys:**
  1. Generate a new key.
  2. Update your application with the new key.
  3. Test the integration and deactivate the old key.

### Best practices for securing API keys:
- Store keys in environment variables.
- Use HTTPS for all API calls.
- Regularly rotate your API keys.
- Restrict key permissions based on usage.

---

## Integration and Usage

### What are the SDKs available for Chimoney API?
Chimoney offers SDKs for the following:
- **PHP (Laravel):** [Laravel SDK Documentation](https://chimoney.io/docs/laravel-sdk)
- Additional SDKs are under development. Stay updated via the [Chimoney GitHub Repository](https://github.com/chimoney).

### How to integrate Chimoney API with different platforms?
1. Follow the platform-specific guides available in our documentation.
2. Use the relevant SDK or directly integrate using REST API calls.
3. Refer to our step-by-step examples for supported platforms.

---

## Error Handling

### How to handle common API errors?
- **400 Bad Request:** Ensure the request format and parameters are correct.
- **401 Unauthorized:** Check your API key and ensure it is active.
- **403 Forbidden:** Confirm you have the necessary permissions.
- **404 Not Found:** Verify the endpoint and resource details.
- **500 Internal Server Error:** Retry the request after some time or contact support.

For more details, refer to the [Error Handling Section](https://chimoney.io/docs/errors).

---

## Support and Community

### How can I get support if I encounter issues?
1. Check our [API Documentation](https://chimoney.io/docs) for troubleshooting steps.
2. Visit the [Support Page](https://chimoney.io/support) to raise a ticket.

### How can I contribute to the Chimoney community?
- Join the Chimoney developer community on [GitHub](https://github.com/chimoney).
- Share feedback and feature requests via our [Support Page](https://chimoney.io/support).
- Contribute to our SDKs or example projects.

---

## Other Common Questions

### How often is Chimoney’s API updated?
We release updates periodically to enhance features, fix bugs, and improve performance. Stay updated by following our [Change Log](https://chimoney.io/docs/changelog).

### Can I test the API before deploying it to production?
Yes, Chimoney provides a sandbox environment for testing. Use your API key in test mode to simulate transactions.

### How do I provide feedback about Chimoney’s API?
We value your feedback! Share your thoughts and suggestions via our [Feedback Form](https://chimoney.io/feedback).

---

For additional assistance, explore our [API Documentation](https://chimoney.io/docs) or contact our support team directly.
