# BigQuery Pricing Overview

BigQuery pricing has two main components:

### Compute Pricing

This refers to the cost to **process queries**, which includes:

- SQL queries  
- User-defined functions (UDFs)  
- Scripts  
- Certain DML (Data Manipulation Language) statements  
- Certain DDL (Data Definition Language) statements

### Storage Pricing

This is the cost to **store data** that you load into BigQuery.

---

## Further Reading on BigQuery Pricing and Optimization

- [Official BigQuery Pricing Documentation](https://cloud.google.com/bigquery/pricing)
- [BigQuery Best Practices for Cost Optimization](https://cloud.google.com/bigquery/docs/best-practices-costs)
- [How to Estimate BigQuery Pricing – Chartio Tutorial](https://chartio.com/resources/tutorials/how-to-estimate-google-bigquery-pricing/)
- [Three Best Practices – Google Cloud Blog](https://medium.com/google-cloud/bigquery-pricing-three-best-practices-ed351a443a38)
- [BigQuery Pricing Guide – CloudBolt](https://www.cloudbolt.io/gcp-cost-optimization/bigquery-pricing/)


---
---
---

## BigQuery Free Tier Overview

Google BigQuery offers a generous free tier to help users get started without incurring costs.

### 🚀 What's Included in the Free Tier?

#### 📊 **Query (Compute) Costs**

- **1 TB of query data processed per month**
  - Applies to on-demand query pricing
  - Reset monthly
  - Shared across all projects linked to the same billing account

#### 💾 **Storage Costs**

- **10 GB of active storage per month**
  - Applies to data loaded into BigQuery
  - Partitioned or unpartitioned tables
  - Reset monthly

---

## ✅ Things to Know

- The free tier is **automatically applied** — no special setup required
- Free tier limits are **not rolled over**
- Exceeding free limits triggers **Blaze pay-as-you-go pricing**
- **Streaming inserts** are **not included** in the free tier (billed separately)

> 💡 Use the free tier for learning, experimentation, or small-scale analytics projects.

---

## Resources

- [BigQuery Pricing](https://cloud.google.com/bigquery/pricing)
- [BigQuery Cost Best Practices](https://cloud.google.com/bigquery/docs/best-practices-costs)


