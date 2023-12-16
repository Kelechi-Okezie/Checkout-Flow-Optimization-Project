# Checkout Flow Optimization Project
## Project Overview
Embark on a practical, real-world journey aimed at optimizing the checkout flow on the 365 online platform. The checkout process is a critical component of online retail, directly impacting conversion rates and customer satisfaction. This project involves a deep dive into an actual database, uncovering insights to enhance the purchase experience for users on the 365 webpage.

## Project Objective
The primary objective is to conduct a thorough analysis of the 365 platform’s checkout process. I will create a comprehensive three-page story-based dashboard from scratch, presenting key metrics, insights, and visualizations spanning from 07-01-2022 to 01-31-2023 using Tableau. By studying the final Tableau story, readers will gain valuable insights and recommendations for potential enhancements to the checkout process and user payment experience.

## User Interaction Categories
To understand user behavior, we categorize interactions into three main types:

Successful Checkout: Users who complete a payment for a subscription without any issues.
Failed Checkout: Users who encounter problems during payment, preventing transaction completion.
Abandoned Cart: Users who add a subscription to their cart but leave without finalizing the payment.

## Key Metrics for Comprehensive Analysis
The developed dashboard will address the following vital metrics, providing a holistic view of the checkout process:

### Monthly Checkout Success Rate:
This metric measures the percentage of successful checkouts compared to monthly attempts. A high rate indicates an efficient checkout process, while a low rate suggests potential areas of improvement.

### Monthly Cart Abandonment Rate: 
This metric shows the percentage of users who added items to their cart but did not complete the purchase. A high abandonment rate may indicate issues such as complicated checkout processes or pricing concerns, hindering customer conversions.

### Identification of Most Common Checkout Errors and Device Correlations: 
By pinpointing common errors during checkout and correlating them with specific devices, we can target technical improvements. This analysis aids in boosting the overall checkout success rate.

## Interpreting the Results
## Current State of Affairs

The Tableau dashboard reveals critical findings related to the checkout flow of the platform: (see dashboard here: https://public.tableau.com/app/profile/kelechi.okezie/viz/365CustomerCheckoutRatesAnalysis/Story1?)
![ms](https://github.com/Kelechi-Okezie/Checkout-Flow-Optimization-Project/assets/141277019/4edb404a-db3d-4c75-97a4-9345b62d8b20)

### >September 2022 witnessed the lowest checkout success rate.
### >October 2022 had the highest cart abandonment rate.
### >The most frequent error encountered during checkout was the "number field is required."
### >While 71% of users attempted to checkout via desktop and 29% via mobile, the most common error message was displayed 502 times for desktop users and escalated to 718 times for mobile users.
Analyzing recent metrics from the checkout process has surfaced vital areas of concern that require immediate attention to optimize sales and improve user experience.

September 2022's dip in the checkout success rate is a clear red flag, hinting at potential underlying issues during that month. The spike in cart abandonment in October 2022 further supports this—suggesting that customers might encounter hurdles in the checkout process that dissuade them from finalizing their purchase.

Of particular concern is the recurring Number Field is Required error. Not only is it the most frequently reported issue, but its higher occurrence on mobile devices—despite a smaller percentage of mobile users compared to desktop—indicates a significant discrepancy in the user experience across platforms. Mobile users seem to face a disproportionately high rate of challenges, which might discourage them from continuing their purchases.

Considering these findings, addressing the Number Field is Required error—with an intensified focus on the mobile user experience—is imperative. Equally important is a thorough review of the checkout process, especially for September and October 2022, to identify and rectify the root causes of these spikes in cart abandonment and low success rates.

## Actionable Insights
Several critical aspects of improvement are possible concerning these specified areas.

### Webpage Interface Enhancements
A webpage interface is pivotal in guiding user interaction—influencing their decisions, and ensuring a smooth, frictionless experience. When users encounter obstacles or confusion during their interaction—especially during critical processes like checkout—the likelihood of abandoning the task rises significantly.

The design intricacies of the checkout screen can be a decisive factor in the user's journey, determining whether they complete the purchase or leave midway. Certain critical elements, like input fields for card details, can appear constrained or be overshadowed by other components on smaller devices or screens. This can lead to users needing to enter the necessary information, leading to errors or transaction failures.

Enhancing the size and overall design of the checkout screen might assist users in entering their card details more efficiently, thereby simplifying and improving the checkout process.

### Demographics
The error message, Your Card was Declined, is roughly three times more prevalent on desktops than mobile devices. Most desktop users might belong to a demographic that has a higher likelihood of using cards that get declined, such as corporate cards or cards from specific banks or regions. Analyzing the user demographics or card types most used on desktops vs. mobiles will provide more precise guidance or support for these particular user segments. For example, users from certain areas might have restrictions on the number of transfers they’re allowed to issue in a single transaction. If so, we could devise a solution to offer users a payment plan in several installments to stay within the transaction limits in these countries.

### Payment Alternatives
Offering alternative payment methods could reduce the abandonment rate due to card issues.
Some customers might face card declines or prefer a different payment method for security or convenience. Introduce options like digital wallets, bank transfers, or buy-now-pay-later services.

Imagine a situation where users are about to purchase your online product, but their preferred credit card gets declined because of a temporary bank error. By introducing alternative payment methods—such as digital wallets or buy-now-pay-later options—you allow these users to spread out their payments or utilize a different payment avenue. This mitigates the risk of transaction decline due to credit card limits and caters to the user's convenience and financial comfort—potentially increasing successful checkouts.

### Real-Time Card Validation
Real-time validation of card details can catch errors before the checkout process advances to the decline stage.

Implement real-time validation on desktop platforms to give immediate feedback if a card number, expiry date, or CVV is incorrectly entered.

For example, imagine a user trying to purchase a product late at night—possibly in a hurry or while being distracted. They might inadvertently mistype the card number or expiry date. Without real-time validation, they would proceed through the checkout process to face a declined transaction. This could lead to frustration, and in some cases, the user might abandon the purchase altogether. By implementing real-time validation, the system can immediately alert the user about the mistake, allowing them to correct it on the spot and continue their purchase smoothly. This enhances user experience and reduces the chances of cart abandonment due to such trivial errors.
