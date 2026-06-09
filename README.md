# 🚚 Bosta — Product Management Case Study

| | |
|---|---|
| **Document Type** | Case Study |
| **Author** | Maram Essam (Product Manager) |
| **Delivered To** | Bosta |
| **Date** | August 25, 2024 |

---

## 📌 Overview

**Bosta Case Study** is a product management case study for building a mobile-first delivery platform tailored to SOHO (Small Office Home Office) sellers in Egypt. It covers the full PM workflow: problem statement, persona definition, MVP vision, user stories, AARRR metrics, wireframing, and risk analysis. It also includes a data analysis section with cohort comparison, pattern discovery, and actionable recommendations to improve user engagement and conversion.

---

## 🚨 Problem Statement

SOHO sellers are struggling to efficiently manage their deliveries due to a lack of accessible, mobile-friendly tools. They need a simple, seamless way to:

- Sign up and onboard without technical barriers
- Create and manage shipping orders from their mobile device
- Schedule pickups at convenient times
- Track their shipments and communicate delays to customers

**Bosta** aims to solve this by providing a user-friendly mobile platform tailored to their needs.

---

## 🔧 Assumptions

- Integrated payment with Bosta so the merchant can pay for registration in-app
- In-house development, design, and customer service teams available
- Product analyst available to track user behavior via Mixpanel or equivalent tool

---

## 👤 Persona

| Attribute | Detail |
|---|---|
| **User Type** | SOHO Seller (Small Office Home Office) |
| **Device** | Mobile app only |
| **Tech Level** | Non-tech savvy |
| **Core Need** | Simple, fast way to manage deliveries end-to-end |

---

## 🎯 MVP Vision

Enable SOHO sellers to seamlessly **sign up**, **create shipping orders**, and **schedule pickups** through a user-friendly mobile experience — with minimal friction from start to first delivery.

---

## 📋 User Stories (MVP Scope)

| User Story | In MVP? |
|---|---|
| As a SOHO seller, I want to easily sign up on Bosta using my mobile device | ✅ Yes |
| As a SOHO seller, I want to create and manage shipping orders from my mobile device | ✅ Yes |
| As a SOHO seller, I want to schedule pickups with a preferred time slot and location | ✅ Yes |
| As a SOHO seller, I want to receive a tracking number for each order | ✅ Yes |
| As a SOHO seller, I want to track shipments in real-time | ❌ No (v2) |
| As a SOHO seller, I want to be notified of delivery issues or delays | ❌ No (v2) |

### Key Acceptance Criteria — Sign Up
- User can complete sign-up within 2 minutes
- Required fields: username, email, password, monthly orders volume, product type, governorate
- Mobile sign-up process is error-free
- User selects a package and pays during registration
- Confirmation email/SMS sent upon successful registration

### Key Acceptance Criteria — Create Shipping Order
- User can add shipping weight, address, and pickup details
- Consignee details: name, email, address, mobile
- AWB (Air Waybill) generated and downloadable as PDF
- Order management page loads within 2 seconds
- Orders can be edited before pickup

### Key Acceptance Criteria — Schedule Pickup
- User can select preferred time slot and location
- Confirmation sent after scheduling
- Pickup can be rescheduled within 1 day if needed

---

## 📊 How to Measure the MVP — AARRR Framework

| Stage | Metric | Goal |
|---|---|---|
| **Acquisition** | Number of SOHO sellers who sign up | 30% of 700K+ SOHO sellers within 3 months |
| **Activation** | % of new users who create first order within 24hrs of sign-up | 60% activation rate |
| **Retention** | % of users who return for a second order within a week | 50% retention in month 1 |
| **Referral** | Number of users who refer other SOHO sellers | 10% referral rate within 3 months |
| **Revenue** | Average Revenue Per User (ARPU) from shipping orders | Cover operational costs and scale profitably |

---

## ⚠️ Risk Analysis

| Risk | Likelihood | Impact | Mitigation Strategy |
|---|---|---|---|
| **Market Acceptance** | Medium | High | Thorough market research pre-launch; targeted marketing; early adopter promotions |
| **User Trust & Security** | High | High | Strict seller verification; secure payment gateways; data protection compliance |
| **Technical Issues** | Medium | High | Rigorous testing before launch; robust monitoring; dedicated technical support team |
| **Competition** | High | Medium | Differentiate with unique features; niche marketing; partnerships with logistics experts |
| **Logistics & Shipping** | Medium | High | Partner with reliable shipping companies; offer shipping insurance; clear handling guidelines |
| **Feature Adoption** | Low | Medium | User training; easy tutorials; collect feedback to iterate; communicate benefits clearly |
| **Customer Support Load** | Low | Medium | Robust FAQ/help section; automated chatbots; scale support team based on demand |

---

## 📈 Data Analysis — Cohort Study

### Overview

A/B/C cohort analysis was conducted on 948 users across three cohorts to identify patterns in profile completion, email verification, and purchasing behavior.

### Cohort Purchase Performance

| Cohort | Toner Units Sold | % of Total |
|---|---|---|
| **Cohort B** | 7,072 | 38% 🏆 |
| **Cohort A** | 6,744 | 36% |
| **Cohort C** | 4,969 | 26% |

> **Winner: Cohort B** generated the most toner sales. Cohort A is a strong competitor and should not be ignored.

---

### Data Summary

| Metric | Cohort A | Cohort B | Cohort C | Total |
|---|---|---|---|---|
| **Users** | 346 | 241 | 361 | 948 |
| **Has First Name** | 60% | 65% | 61% | 61% |
| **Has Last Name** | 83% | 88% | 86% | 85% |
| **Verified Email** | 48% | 96% | 30% | 53% |
| **Has Phone Number** | 33% | 30% | 24% | 29% |

---

### Patterns & Theories

1. **Email Verification drives purchases** — Cohort B has the highest verified email rate (96%) and the highest purchase volume. Email verification is strongly correlated with purchasing behavior and is a critical step in the conversion funnel.

2. **Phone number collection signals intent** — Users who provide phone numbers are more invested in the platform. Only 29% of users overall provide phone numbers, representing a significant engagement opportunity.

---

### Recommendations

1. **Boost Email Verification** — Target Cohort C (only 30% verified) with reminders and incentives to verify emails, which is directly linked to higher purchases.

2. **Encourage Profile Completion** — Incentivize users to complete their profiles (first name, last name, phone number) for a more personalized experience, especially in Cohort C.

3. **Target Cohort C** — Launch targeted campaigns with special offers and incentives for profile completion and email verification to unlock Cohort C's potential.

---

## 📁 Repository Contents

```
📁 Bosta-Case-Study/
├── 📄 README.md
└── 📄 Bosta - Case study.pdf
```

---

*Author: Maram Essam | PM Portfolio Case Study | August 2024*
