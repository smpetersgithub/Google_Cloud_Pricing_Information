# Firebase Pricing

-------------------------------------------------

### Relevant links

The following link gives an overview of pricing plans and provides a calculator.    
[Firebase Pricing](https://firebase.google.com/pricing)  

The FAQ has a lot of good information here.    
[Firebase Pricing FAQ](https://firebase.google.com/support/faq#pricing)

------------------------------------------------

# From the FAQ....

## How do I know which pricing plan is right for me?

For detailed information about pricing plans, see Firebase pricing plans.


### Spark pricing plan

Our Spark plan is a great place to develop your app at no cost. You get all the no-cost Firebase features (Analytics, Remote Config, Crashlytics, and so on) and generous amounts of our paid infrastructure features. **However, if you exceed your Spark plan resources in a calendar month, your app will be shut off for the remainder of that month.** In addition, Google Cloud features are not available when using the Spark plan.

### Blaze pricing plan

Our Blaze plan is designed for production apps. The Blaze plan also allows you to extend your app with paid Google Cloud features. You pay only for the resources that you consume, allowing you to scale with demand. We strive to make our Blaze plan prices competitive with industry-leading cloud providers. 

------------------------------------------------

## How is the no-cost usage in the Blaze plan different from the no-cost usage in the Spark plan?

No-cost usage on the Blaze plan is calculated daily. Usage limits also differ from the Spark plan for Cloud Functions, phone authentication, and Test Lab.

### Cloud Functions

No-cost usage on the Blaze plan is calculated at the **Cloud Billing account level**, not the project level, and includes the following limits:

- 2M invocations/month  
- 400K GB-seconds/month  
- 200K CPU-seconds/month  
- 5 GB of networking egress/month

### Phone Authentication

No-cost usage on the Blaze plan is calculated **monthly**.

### Test Lab

No-cost usage on the Blaze plan has the following limits:

- 30 physical device minutes/day  
- 60 virtual device minutes/day



----------------------
----------------------
----------------------
----------------------
----------------------



# Firebase Pricing Plans Overview

Firebase offers two primary pricing plans to support projects from prototype to production:

### Spark Plan (Free)

The Spark plan is ideal for small projects and personal apps. It includes a generous free tier of Firebase services.

**Key Features:**

- $0/month — free forever
- Includes core Firebase services:  
  - **Analytics**, **Crashlytics**, **Performance Monitoring**, **Remote Config**, and more
- Limited access to paid infrastructure:
  - Realtime Database, Firestore, Hosting, Cloud Functions, etc., have usage quotas
- No access to **Google Cloud** services
- Resources reset **monthly**
- Project is **suspended** for the rest of the month if limits are exceeded

> ⚠️ Great for development and testing, not suitable for scaling apps in production.

---

### Blaze Plan (Pay as You Go)

The Blaze plan is designed for production-grade apps, offering full flexibility and scalability.

**Key Features:**

- Billed monthly — pay only for what you use
- All Spark plan features, **plus:**
  - **Google Cloud integration**
  - **Higher limits** and **automatic scaling**
- Ideal for apps needing:
  - High traffic capacity
  - Custom domains
  - Advanced backend logic via Cloud Functions

> ✅ Highly recommended for growing or production applications.

---

### No-Cost Usage Comparison

| Feature                  | Spark Plan       | Blaze Plan (Free Tier) |
|--------------------------|------------------|-------------------------|
| Cloud Functions          | Limited quota    | Free tier (shared by billing account) |
| Phone Authentication     | Limited quota    | Free monthly quota     |
| Test Lab                 | Limited daily use| More generous daily limit |

For more, see:  
- [Firebase Pricing](https://firebase.google.com/pricing)  
- [Firebase Pricing FAQ](https://firebase.google.com/support/faq#pricing)


