---
id: 10dlc
slug: /
---

import Lead from "@site/src/components/Lead";

# Registering 10DLC brands and campaigns

<Lead>
  This guide explains how to register your brand and campaign through Wavix to send messages using 10-digit long codes (10DLCs)
</Lead>

## What is 10DLC?

10DLC stands for "10-digit long codes." They're phone numbers that businesses can use to send text messages in the US.

Businesses often prefer 10DLCs over short codes ("456789") or toll-free numbers ("800-555-1234") because they look like regular local phone numbers ("(740) 555-4567").

Mobile carriers in the US want to ensure that application-to-person (A2P) messaging isn't used for spamming or other harmful purposes. They consider all messages (SMS and MMS) sent using a messaging provider like Wavix to be A2P traffic.

Before using 10DLCs as sender IDs for A2P messaging, you must register your [brand](#registering-a-10dlc-brand) and [campaign](#registering-a-10dlc-campaign) with [the Campaign Registry (TCR)](https://www.campaignregistry.com/), the central hub for registering A2P messaging campaigns in North America.

The Wavix platform allows you to register 10DLC brands and campaigns directly from the user interface.

:::note
You don't need to register a brand or campaign to send messages using short codes or toll-free numbers.
:::

:::warning
Always provide complete, accurate, and up-to-date details when registering your brand and campaign. The information you enter may affect message throughput.
:::

## Registering a 10DLC brand

Before you can send text messages using 10DLCs, you must verify your identity by registering your brand with TCR.

Follow the steps in this section to register your 10DLC brand through Wavix.

:::info[Important]
Mobile carriers approve each brand registration and determine message throughput based on the submitted brand details.
:::

### Registration types

Depending on the legal status of your business, you can choose either _quick_ or _standard_ brand registration.

#### Quick registration

You can only choose quick registration if you're a sole proprietor without an [EIN](https://www.irs.gov/businesses/employer-identification-number) (or tax ID for companies outside the US). This process requires you to provide fewer details than standard registration but limits you to a single 10DLC phone number with low message throughput.

#### Standard registration

If you're a business with an EIN or tax ID (such as an LLC or corporation), you must choose standard registration. This process requires detailed company information but offers higher throughput. You can create up to fifty 10DLC campaigns, with up to forty-five 10DLC phone numbers per campaign.

### Registering your brand

To register your brand through Wavix:

1. Go to **Register your Brand**.
2. On the **Registration type** page, choose either **Quick** or **Standard** registration depending on your business type. Select **Next**.
3. On the **Brand details** page, enter your **Company details**:
   - **Brand name**
   - **Website** (optional for quick registration)
   - **Company legal name**
   - **Business industry or vertical**
   - **Country of registration**
   - **EIN or Tax ID**
   - **Company type** (if applicable)
   - **Stock exchange** (for publicly traded companies)
   - **Stock symbol** (for publicly traded companies)
4. Enter the **Contact details** of the business owner (quick registration) or the person filing the brand registration request (standard registration):
   - **First name**
   - **Last name**
   - **Support phone number**
   - **Support email**
   - **Street address**
   - **City**
   - **State or province**
   - **Country**
   - **Zipcode or postal code**
     :::warning
     The company's business address must match the legal address in the registration documents.
     :::
5. Select **Next**.
<figure>
![Screenshot of the page for entering brand registration details](/img/registration.jpg)
<figcaption>Entering brand details for registration</figcaption>
</figure>

6. On the summary page, review your brand details. Select **Back** to fix any errors. If the information is correct, confirm a non-refundable brand registration fee and select **Submit**.

### Registration status

After you submit your brand registration request, TCR checks against several databases and uses verification software to confirm the accuracy of your information. They make sure that your company exists, and that its records match the details you provided, paying special attention to your business's legal name, address, and EIN or tax ID.

Your brand registration can have one of the following statuses:

- **Pending** — TCR has not yet made a decision regarding your brand registration.
- **Verified** — TCR has verified your brand. Now, [register your campaign](#registering-a-10dlc-campaign).
- **Vetted_Verified** — TCR has verified your brand after requesting external vetting. You are free to [register your campaign](#registering-a-10dlc-campaign).
- **Unverified** — TCR couldn't verify your brand due to missing or incorrect information. Amend your details and [resubmit the registration](#registering-your-brand).

:::tip
Wavix provides feedback to help you identify possible inaccuracies in your data.
:::

## Registering a 10DLC campaign

Once you've [registered your brand](#registering-a-10dlc-brand), you must register your campaign to tell TCR how you're going to use 10DLC messaging. Each 10DLC campaign should describe your specific use case and specify the content of your messages.

Follow the steps in this section to register your 10DLC brand through Wavix.

:::info[Important]
Before registering a 10DLC campaign:

- Your brand must be verified.
- You must have an active US local phone number on your account.
  :::

### Entering campaign details

To register your brand through Wavix:

1. Go to **Register your campaign and outbound numbers (aka 10DLCs or Sender IDs)**.
2. On the **Campaign details** page, enter your **Campaign name** for reference purposes and a detailed **Campaign description**.
3. Under **Select Use case**, choose a use case that best describes your messaging scenario:
   - **Standard** use cases are available for all registered brands and don't need additional approval from mobile carriers.
   - **Special** use cases are sensitive or critical in nature and may require additional approval from mobile carriers.
     :::warning
     Once you've created a campaign, you cannot change its use case.
     :::
4. Select **Next**.
<figure>
![Screenshot of the page for entering campaign details and choosing a use case](/img/details.jpg)
<figcaption>Entering campaign details and choosing a use case</figcaption>
</figure>
:::info[Important]
Your campaign description, use case, and message samples must be as exact as possible. Mobile carriers may check if the details you provided match the content of your messages.
:::

### Entering campaign content

To specify your campaign content:

1. On the **Campaign content** page, provide up to five **Message samples**, depending on the selected use case.
   :::tip
   Provide exact samples without using placeholders or variables in the message body.
   :::
2. Select all **Campaign attributes** that apply to your campaign and message content using the **YES/NO** toggles.
3. Select **Next**.
<figure>
![Screenshot of the page for entering message samples and selecting campaign attributes](/img/samples.jpg)
<figcaption>Entering message samples and selecting campaign attributes</figcaption>
</figure>

### Adding keywords (optional)

Wavix supports all standard opt-in (START and UNSTOP) and opt-out (STOP, QUIT, and USUBSCRIBE) keywords by default.

To specify additional keywords:

1. On the **Additional keywords** page, provide comma-separated lists of **Opt-in**, **Opt-out**, and **Help** keywords. For example, `SUBSCRIBE,YES,ENROLL`.
   :::info[Important]
   The keywords you enter are case-sensitive.
   :::
2. Enter the message your customers will receive in response to each keyword type. US mobile carriers require you to provide a response (acknowledgment) when someone sends any opt-in or opt-out keywords.
3. Select **Next**.
   <figure>
   ![Screenshot of the page for specifying additional opt-in, opt-out, and help keywords](/img/keywords.jpg)
   <figcaption>Specifying additional opt-in, opt-out, and help keywords</figcaption>

   </figure>

### Adding phone numbers

You can add up to five phone numbers to each campaign, depending on the registration process selected.

On the **Numbers** page, choose the 10DLCs you want to use as sender IDs and select **Next**.

<figure>
![Screenshot of the page for adding phone numbers](/img/campaign.jpg)
<figcaption>Adding phone numbers</figcaption>
</figure>

:::note
You can assign each phone number only to one campaign. If a phone number is grayed out, it means it's assigned to a different campaign. To use it, first unassign it from the other campaign.
:::

### Reviewing campaign details

The **Summary** page allows you to review your campaign details. Select **Back** to fix any errors. If the information is correct, select **Confirm** to complete your registration.

<figure>
![Screenshot of the summary page](/img/summary.jpg)
<figcaption>Reviewing campaign details</figcaption>
</figure>

:::note
We'll automatically deduct campaign registration and monthly fees for the first three months from your account.
:::

Standard use case campaigns are automatically approved and become active. Special use case campaigns may require additional approval by mobile carriers before activation.

Once the campaign is active, you can start messaging.
