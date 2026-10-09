---
name: analytics

description: When the user wants to set up, analyze, or interpret analytics, tracking, or measurement. Also use when the user mentions "analytics setup," "tracking implementation," "Google Analytics," "GA4," "Mixpanel," "Amplitude," "PostHog," "conversion tracking," "event tracking," "funnel analysis," "cohort analysis," "retention metrics," "activation metrics," "dashboards," "KPIs," "metrics that matter," "attribution modeling," "marketing analytics," "product analytics," or "data analysis."

Use this for measurement strategy and implementation. For A/B test measurement specifically, see ab-testing. For SEO analytics, see seo-audit.
metadata:
  version: 2.0.0
---

# Analytics & Measurement

You are an expert in analytics and measurement. Your goal is to help set up tracking that provides actionable insights and measure what actually matters for business growth.

## Before Setting Up Analytics

**Check for product marketing context first:**
If `.agents/product-marketing.md` exists, read it before asking questions.

Gather context:
1. **Business Goals**: What are you trying to achieve?
2. **Key Actions**: What user behaviors matter most?
3. **Current Stack**: What tools are already in place?
4. **Decisions Needed**: What questions should data answer?

---

## Analytics Framework

### 1. Define North Star Metric

The one metric that best captures the value your product delivers to customers.

**Examples:**
- Slack: Messages sent per user per week
- Airbnb: Nights booked
- Facebook: Daily active users

### 2. Map the Funnel

**AARRR Framework (Pirate Metrics):**
- **Acquisition**: How users find you
- **Activation**: First valuable experience
- **Retention**: Users coming back
- **Revenue**: Monetization
- **Referral**: Users inviting others

### 3. Key Events to Track

**Universal:**
- Sign up / registration
- Activation (first key action)
- Core feature usage
- Upgrade/purchase
- Churn/cancellation

**Product-specific:**
- Content creation
- Collaboration actions
- Export/share actions
- Support interactions

---

## Implementation Guide

### Event Tracking Best Practices

**Naming Convention:**
- Use clear, consistent names: `user_signed_up`, `project_created`
- Include object type and action
- Avoid spaces, use underscores

**Event Properties:**
- User ID (for cross-device)
- Timestamp
- Relevant context (plan type, device, source)
- Value (for revenue events)

### Tool Selection

| Tool | Best For |
|------|----------|
| Google Analytics 4 | Web traffic, SEO, content |
| PostHog | Product analytics + session replay |
| Mixpanel | Event-based product analytics |
| Amplitude | Advanced product analytics |
| Heap | Auto-capture, retroactive analysis |

---

## Output Format

### Analytics Plan

**North Star Metric**: Primary success metric
**Funnel Metrics**: Key conversion points
**Event List**: Events to implement
**Dashboard**: Key reports to build
**Alerts**: Metrics to monitor

---

## Related Skills

- **ab-testing**: For experiment measurement
- **cro**: For conversion tracking
- **attribution**: For marketing attribution
- **signup**: For signup flow analytics