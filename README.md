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
Stakeholders in e-commerce ecosystems are individuals, groups, or entities that influence or are influenced by the system’s operations, objectives, or outcomes. These stakeholders can be categorized as primary, secondary, or negative, depending on their relationship to the system.

| Requirements    | Descriptions |
|----------------|----------|
| **Customer (Register User / Guest User)**  | Allow users to register accounts or see as guests with basic functionality. |
| **View Product (images, Videos, Related products, Up sell products, Cross sell Products)**     | Display product details including media, related items, and recommendations. |
| **AI Powered E-Commerce**    | Implement AI for personalized recommendations, search improvements, and automated customer interactions. |
| **Product Status (Active/ Disable)** | Allow admin to activate or disable products. Disabled products shouldn't appear in searches. Status changes should update inventory systems. Customers should see "out of stock" for disabled items. |
| **Add items to Cart** | Enable adding multiple products to cart. Show real-time cart updates and totals. Allow quantity adjustments. Support saving carts for later purchase. And remove something if don’t like. |
| **Purchase Product** | Provide clear checkout process steps. Show order summary before payment. Send immediate confirmation emails. Allow order tracking after purchase. |
| **Payment Method** | Support multiple payment options (PayPal and Cash on Delivery). Process payments in multiple currencies. Allow saved payment methods for registered users. |
| **Customer Support** | Offer multiple contact channels (chat, email). Include FAQ and help center. Enable support ticket creation. Provide order-specific assistance. |
| **Account Manager (Admin)** | Give admin full dashboard access. Allow user management and role assignments. Enable order processing capabilities. Provide sales and inventory oversight. |
| **Shipping Method** | Offer various shipping options with costs. Integrate with carrier APIs for rates. Allow shipping restrictions by location. Provide tracking information to customers. |
| **Review and Feedback** | Enable customers to rate products. Allow written reviews with images. Moderate inappropriate content. Show aggregate ratings on product pages. |
| **Confirm Transaction details** | Display complete order summary pre-purchase. Send detailed confirmation emails. Allow invoice downloads. Show payment method used in confirmation. |
| **User Account Update** | Let users edit personal information. Enable password changes. Allow address book management. Provide subscription preference options. |
| **Monitor sales and expenses** | Track revenue and costs in real-time. Generate profit/loss reports. Monitor product performance. Provide visual dashboards for metrics. |
| **Marketing (Promotions, Communications, Search and SEO)** | Support discount codes and campaigns. Enable email marketing integration. Optimize for search engines. Provide analytics for marketing efforts. |
| **Reporting (Sales, Customers, Products)** | Generate customizable reports. Export data for analysis. Track customer acquisition. Monitor inventory turnover rates. |
| **Taxes** | Automatically calculate applicable taxes. Support regional tax rules. Allow tax-exempt customers. Generate tax reports for accounting. |

# Stakeholder Analysis
Stakeholders in e-commerce ecosystems are individuals, groups, or entities that influence or are influenced by the system’s operations, objectives, or outcomes. These stakeholders can be categorized as primary, secondary, or negative, depending on their relationship to the system.

| Stakeholder    | Analysis |
|----------------|----------|
| **Investors**  | Investors who have put **money** into the ride-sharing service and expect a return on their **investment**. These investors may include **venture capitalists**, **angel investors**, or **institutional investors**. |
| **Riders**     | People who use the ride-sharing service to get from one place to another. These individuals have a stake in the success of the service because they **rely** on it for **transportation**. |
| **Drivers**    | Individuals who work for the ride-sharing service and **provide rides** to **riders**. Drivers have a stake in the success of the service because their **livelihood** depends on it. |
| **Administrators** | People who are responsible for managing the ride-sharing service, including making **decisions about pricing**, **marketing**, and **customer support**. |
| **Regulators** | **Government agencies** or other entities that have **regulatory authority** over the ride-sharing service. These regulators may have an interest in ensuring that the service operates in compliance with **local laws** and **regulations**. |
| **Competitors** | Other companies that offer ride-sharing services and may be **impacted** by the success of the service. |





# Quality Attribute








