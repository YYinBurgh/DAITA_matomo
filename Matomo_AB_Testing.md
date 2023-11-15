# Matomo A/B Testing for Web Traffic Randomization 🚦

## Table of Contents 📚

- [Introduction](#introduction-)
- [Step-by-Step Guide](#step-by-step-guide-)
- [Setting Up Matomo on Your Website](#setting-up-matomo-on-your-website-)
- [Creating an A/B Test in Matomo](#creating-an-ab-test-in-matomo-)
- [Implementing Variations](#implementing-variations-)
- [Starting and Monitoring the A/B Test](#starting-and-monitoring-the-ab-test-)
- [Analyzing the Results](#analyzing-the-results-)
- [Additional Information](#additional-information-)

## Introduction 🌟

Matomo's A/B Testing is a powerful tool for optimizing web traffic across different landing pages. This README outlines the workflow for conducting A/B testing using Matomo. Steps and options may vary depending on your needs and the Matomo version. For detailed instructions, check out [Matomo's A/B Testing User Guide](https://matomo.org/guide/reports/a-b-testing/).


![image](https://github.com/YYinBurgh/DAITA_matomo/assets/69682190/3e0e73c6-ee18-4751-acdb-b5fc9b11a699)

## Step-by-Step Guide 🛠️

### Step 1: Installation and Activation
- Install and activate the A/B testing plugin in your Matomo dashboard.

### Step 2: Create a New A/B Test
- Navigate to A/B testing and initiate a new test.

### Step 3: Test Setup
- Define your test including name, hypothesis, URLs, and visitor percentage.

### Step 4: Variations
- Create two variations for your landing pages in the "Variations" section.

### Step 5: Success Metrics
- Choose what user action constitutes a successful visit.

### Step 6: Start Experiment
- Begin your A/B test and let Matomo route visitors accordingly.

### Step 7: Monitor Performance
- Keep an eye on each variation's performance in the Matomo dashboard.

## Setting Up Matomo on Your Website 🌐

To integrate Matomo with your Weebly website, follow these steps:

1. Log into your Matomo dashboard.
2. Find the "Tracking Code" in the "Administration" section.
3. Copy this code and paste it into the "Header Code" section of your Weebly site's "SEO" settings.

## Creating an A/B Test in Matomo 🎯

- Log in to your Matomo dashboard.
- Navigate to the "A/B Testing" section.

### Section I: Definition
- Click "Create New A/B Test".
- Define the A/B test's parameters, like name and hypothesis.
- Enter the name of the A/B test. Ex: “DistributeAudience”
- Define the hypothesis for your test. Ex: “The new homepage design at 'https://ahafitness.weebly.com/untitled.html' will convert better than the current homepage.”
- Give a Description for this test. Ex: “Comparing two landing pages.”
- Add many Variations you want to the Original landing page and name them as you wish. Ex: “NewHomepage”

### Section II: Success Metrics
- Choose a conversion metric that you want to track. This can be clicks, page views, form completions, or any other action that is important to your website.

### Section III: Success Conditions
- Minimum Detectable Effect (MDE):
This is the smallest change in performance between variations that you want to be able to detect in your test. For example, if your current conversion rate is 10% and you expect a 20% MDE, your new variation needs to achieve a conversion rate of 12% to be declared as the winner. Depending on your expectations, you can set this to 10% for a small effect, 40% for a medium effect, or 70% for a large effect.

- Confidence Threshold:
This is the probability that the difference in performance between the variations is not due to random chance. A higher value means that you can be more confident in the results. Typically, this value is set at 95%, meaning there's a 5% chance that you might be wrong in declaring the winning variation.

### Section IV: Target Pages
- Specify the URL of the page you're testing.
- Ex: which is your main homepage with the conditions: "https://ahafitness.weebly.com/".

### Section V: Target Allocation
- Determine the visitor percentage for the test.
- Set the percentage of visitors to include in the test. As you want to distribute the traffic equally, set it to 100%.

### Section VI: Redirects
- Set up redirects for each variation.
- Ex: For the Variation named "NewHomepage", choose the 'Redirects to a new page' implementation and enter the URL of the new homepage: "https://ahafitness.weebly.com/untitled.html".

### Section VII: Schedule
- Schedule the duration of your test.
- Depending on the traffic to your site, this could range from a few days to several weeks. For instance, set the test to run for four weeks from the start date. Adjust this timeframe based on your site's traffic and the statistical significance you want to achieve.

### Section VIII: Embedded Code
- Insert the provided JavaScript tracking code on all relevant pages.
- Once the test is created and updated in all fields, Matomo will provide you with a JavaScript tracking code. You'll need to insert this code on all pages that are part of the test, as well as any other pages you want to track interactions on. This code will automatically handle the redirection of users based on the test configuration.

## Implementing Variations 🔄

Manually implement changes on your Weebly site to reflect test variations by creating different versions of your webpages.

## Starting and Monitoring the A/B Test 🔍

- After creating and implementing the variations, go back to the Matomo dashboard.
- Navigate to the "A/B Testing" section.
- Find the test you created and click "Start Test".
- Matomo will start tracking the performance of the different variations of your webpage. You can monitor the progress of the test in real-time on the Matomo dashboard.
- Monitor real-time progress and performance of each variation.

## Analyzing the Results 📊

After a significant duration, analyze the test results in the Matomo A/B testing dashboard to determine the more effective variant.

## Additional Information ℹ️

Matomo uses cookies for identifying repeat visitors, ensuring they see the same variant on subsequent visits. This comprehensive setup provides a robust framework for A/B testing with Matomo.

