# Architectural Decoding of Bagisto: Scalability, Modularity, and Design Patterns in a Laravel-Powered eCommerce Ecosystem

 **MD MAHADI HASAN, MD ASHIKUR RAHMAN, NABIRA JAHAN LIMU, ASIFA ASRAFI, YEASIR ARAFAT SHANTU**

 

## History Log

- **2025, April 8**: *Task Description: Initial setup of project structure and documentation* – **Mahadi**


## Table of Contents
- [Introduction](#Introduction)
- [Business Requirements](#Business_Requirements)
- [Stakeholder Analysis](#Stakeholder_Analysis)
- [Quality Attribute](#Quality_Attribute)


  

# Introduction

# Business Requirements
To understand the architecture of the Bagisto shopping website in depth, it’s important to first outline the core business requirements. These requirements provide a clear foundation for the system’s design, ensuring it effectively supports the platform’s goals, user needs, and overall functionality for smooth online shopping experiences.

| Requirements    | Descriptions |
|----------------|----------|
| **Customer (Register User / Guest User)**  | Allow users to register accounts or see as guests with basic functionality. |
| **View Product (Images, Videos, Related Products, Up Sell Products, Cross Sell Products)**     | Display product details including media, related items, and recommendations. |
| **AI Powered E-Commerce**    | Implement AI for personalized recommendations, search improvements, and automated customer interactions. |
| **Product Status (Active/ Disable)** | Allow admin to activate or disable products. Disabled products shouldn't appear in searches. Status changes should update inventory systems. Customers should see "out of stock" for disabled items. |
| **Add Items To Cart** | Enable adding multiple products to cart. Show real-time cart updates and totals. Allow quantity adjustments. Support saving carts for later purchase. And remove something if don’t like. |
| **Purchase Product** | Provide clear checkout process steps. Show order summary before payment. Send immediate confirmation emails. Allow order tracking after purchase. |
| **Payment Method** | Support multiple payment options (PayPal and Cash on Delivery). Process payments in multiple currencies. Allow saved payment methods for registered users. |
| **Customer Support** | Offer multiple contact channels (chat, email). Include FAQ and help center. Enable support ticket creation. Provide order-specific assistance. |
| **Account Manager (Admin)** | Give admin full dashboard access. Allow user management and role assignments. Enable order processing capabilities. Provide sales and inventory oversight. |
| **Shipping Method** | Offer various shipping options with costs. Integrate with carrier APIs for rates. Allow shipping restrictions by location. Provide tracking information to customers. |
| **Review And Feedback** | Enable customers to rate products. Allow written reviews with images. Moderate inappropriate content. Show aggregate ratings on product pages. |
| **Confirm Transaction Details** | Display complete order summary pre-purchase. Send detailed confirmation emails. Allow invoice downloads. Show payment method used in confirmation. |
| **User Account Update** | Let users edit personal information. Enable password changes. Allow address book management. Provide subscription preference options. |
| **Monitor Sales And Expenses** | Track revenue and costs in real-time. Generate profit/loss reports. Monitor product performance. Provide visual dashboards for metrics. |
| **Marketing (Promotions, Communications, Search And SEO)** | Support discount codes and campaigns. Enable email marketing integration. Optimize for search engines. Provide analytics for marketing efforts. |
| **Reporting (Sales, Customers, Products)** | Generate customizable reports. Export data for analysis. Track customer acquisition. Monitor inventory turnover rates. |
| **Taxes** | Automatically calculate applicable taxes. Support regional tax rules. Allow tax-exempt customers. Generate tax reports for accounting. |

With the business requirements now established, we can shift our focus to designing the architecture of the Bagisto shopping site to ensure it meets functionality, scalability, and performance needs.

# Stakeholder Analysis
Stakeholders in e-commerce ecosystems are individuals, groups, or entities that influence or are influenced by the system’s operations, objectives, or outcomes. These stakeholders can be categorized as primary, secondary, or negative, depending on their relationship to the system.

**Primary Stakeholders**

| Stakeholder    | Analysis |
|----------------|----------|
| **Customers**  | End-users purchasing goods/services; central to revenue generation and user experience. |
| **Business Owners/Shareholders**     | Entities investing capital and driving strategic decisions to maximize profitability. |
| **Employees**    | Staff involved in platform development, marketing, customer support, and logistics (e.g., developers, sales teams). |
| **Suppliers/Vendors** | Third-party providers of goods, raw materials, or services integrated into the platform.|
| **Payment Gateways** | Financial intermediaries (e.g., PayPal, Stripe) enabling secure transaction processing. |
| **Logistics Partners** | Delivery and warehousing firms ensuring order fulfillment (e.g., FedEx, DHL). |


**Secondary Stakeholders**

| Stakeholder    | Analysis |
|----------------|----------|
| **Regulatory Bodies**  | Government agencies enforcing compliance with laws (e.g., GDPR, consumer protection, taxation). |
| **Technology Providers**     | Companies supplying infrastructure (e.g., cloud services like AWS, cybersecurity tools). |
| **Marketing Agencies**    | External teams managing brand visibility and customer acquisition campaigns. |
| **Local Communities** | Populations impacted by the e-commerce system’s environmental or economic footprint (e.g., warehouse locations). |
| **Industry Associations** | Organizations setting standards or advocating for sector-wide practices (e.g., Digital Commerce Alliance). |

**Negative Stakeholders**

| Stakeholder    | Analysis |
|----------------|----------|
| **Competitors**  | Rival businesses seeking to undermine market share through aggressive pricing or innovation. |
| **Cybercriminals**     | Malicious actors exploiting vulnerabilities for fraud, data breaches, or service disruptions. |
| **Privacy Activists**    | Groups opposing data collection practices perceived as invasive or unethical. |
| **Environmental Activists** | Organizations critiquing unsustainable practices (e.g., excessive packaging, carbon emissions from logistics).|
| **Counterfeit Sellers** | Unauthorized third parties distributing fake products through the platform, damaging brand integrity. |
| **Regulators (in non-compliance scenarios)** | Authorities imposing fines or sanctions for violations of legal/ethical standards. |






# Quality Attribute








