---
id: 10dlc
slug: /
---

import Lead from "@site/src/components/Lead";

# Registering 10DLC brands and campaigns

<Lead>
  This guide explains how to register your brand and campaign to send messages using 10-digit long codes (10DLCs)
</Lead>

## What is 10DLC?

10DLC stands for "10-digit long codes." They're phone numbers that businesses can use to send text messages in the US.

Unlike short codes (like "56789") or toll-free numbers (like "1-800-555-1212"), 10DLCs look like regular local phone numbers (like "(555) 123-4567") .

Mobile carriers in the US consider all messages (SMS and MMS) sent using a messaging provider like Wavix to be application-to-person (A2P) traffic.

To use 10DLCs as sender IDs for application-to-person messaging, you must register your [brand](#10dlc-brand-registration) and [campaign](#10dlc-campaign-registration) with [the Campaign Registry (TCR)](https://www.campaignregistry.com/).

:::note
You don't need to register your brand or campaign to send messages using short codes or toll-free numbers.
:::

The Wavix platform allows you to register 10DLC brands and campaigns directly from the user interface.

:::warning
Always provide complete, accurate, and up-to-date details during the registration. The information you enter may affect message throughput.
:::

## 10DLC brand registration

Before you can send text messages using 10DLCs, you must verify your identity by registering your brand. Follow the steps in this section to register your brand in Wavix.

:::note
Mobile carriers pre-approve each brand registration and automatically allocate message throughput based on the submitted brand details and message content.
:::

### Registration types

Depending on the legal status of your business, you can choose either **quick** or **standard** brand registration.

#### Quick registration

You can only choose quick registration if you're a sole proprietor without an [EIN](https://www.irs.gov/businesses/employer-identification-number) (or tax ID for companies outside the US). This process requires you to provide fewer details than standard registration but limits you to a single 10DLC phone number with low messaging throughput.

#### Standard registration

If you're a business with an EIN or tax ID (such an LLC or corporation), you must choose standard registration. This process requires detailed company information but offers higher throughput. You can have up to fifty 10DLC campaigns, with up to forty-five 10DLC phone numbers per campaign.

### Registering a brand

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
4. Enter **Contact details** of the business owner (quick registration) or the person filing the brand registration request (standard registration):
   - **First name**
   - **Last name**
   - **Support phone number**
   - **Support email**
   - **Street address**
   - **City**
   - **State or province**
   - **Country**
   - **Zipcode or postal code**
     :::info
     The company’s business address must match the legal address in the registration documents.
     :::
5. Select **Next**.
    <figure>

   ![registration](/img/registration.jpg)

    <figcaption>Entering brand details for registration</figcaption>
    </figure>

6. Review the details you've entered on the brand registration summary page. Select **Back** to update any of the fields.
7. If the information is correct, confirm a non-refundable brand registration fee and select **Submit**.

### Brand registration status

The brand registration status is based on the accuracy of the submitted information. The Campaign Registry (TCR) Administrator will locate and confirm the existence of the Company you submitted by checking against several databases and utilizing verification software. Correct legal company name and address, EIN or Tax ID are extremely important for obtaining a ‘Verified’ status.

If your brand can not be verified, you can resubmit the form after updating the brand details.

Wavix provides feedback to help you identify possible data inaccuracies.

## 10DLC campaign registration

### Before you begin

Before registering a 10DLC campaign, you need to have an active US local phone number on your account.

### Registering a campaign

- Register your campaign and outbound numbers (aka 10DLCs or Sender IDs)

Each 10DLC campaign should describe your specific use case, and the content of SMS and MMS actually sent.

To register a new 10DLC campaign, you need to provide the following information:

- A campaign name that will be used for reference purposes
- A detailed campaign description
- Use case that describes your messaging scenario
- Exact examples of messages that will be sent

:::info[Important]

The campaign description, Use case, and message samples need to be as exact as possible. Mobile carriers may check them to confirm if the provided details actually apply to the content of messages being sent.

:::

<figure>

![details](/img/details.jpg)

<figcaption>Fig. 2 Campaign details and use case</figcaption>

</figure>

Depending on the selected Use case, you would need to provide up to five message examples. We recommend you provide exact samples without using placeholders or variables in the message body.

<figure>

![samples](/img/samples.jpg)

<figcaption>Fig. 3 Message samples</figcaption>

</figure>

Select all the campaign attributes that apply to your campaign and message content using the YES/NO toggle.

Click Next to specify additional details of your campaign.

### Handling keywords (Optional)

Wavix supports all standard opt-in and opt-out keywords by default. Please note that all additional keywords are case-insensitive.

#### Handling STOP keywords

Add custom, comma-separated opt-out keywords if needed. US mobile carriers require you to provide a response (aka acknowledgment) when a person sends any STOP keyword. Enter the acknowledgement message your customers will receive if they opted out.

#### Handling START keywords

Add custom, comma-separated opt-in keywords if needed. US mobile carriers require you to provide a response when a person sends any START keyword. Enter the acknowledgement message your customers will receive if they opted in.

#### Handling HELP keywords

Your customers might reply with the word "HELP" or any custom HELP keyword to learn more about the messages that they're receiving from you. List all comma-separated HELP keywords and specify the message to be sent back when any of the HELP keywords are received.

<figure>

![keywords](/img/keywords.jpg)

<figcaption>Fig. 4 Additional opt-in, opt-out, and help keywords</figcaption>

</figure>

### Adding phone numbers to your campaign

You can add up to five phone numbers to your campaign, depending on the registration process selected. Choose the numbers you want to use as sender IDs and click Next.

<figure>

![campaign](/img/campaign.jpg)

<figcaption>Fig. 5 10DLCs for the campaign</figcaption>

</figure>

:::info[Important]

Each phone number can be assigned to a single campaign only. If the phone number is grayed out, you need to unassign it from the campaign it is currently linked to.

:::

### Summary and the campaign registration

Review your campaign details. In case of any errors click Back and update the necessary fields. Click Register to complete the wizard.

<figure>

![summary](/img/summary.jpg)

<figcaption>Fig. 6 Campaign summary</figcaption>

</figure>

:::note
Campaign registration and monthly fees for the first three months will be deducted from your account automatically.
:::

Standard Use case campaigns are automatically approved and become Active. Special Use case campaigns may require additional approval by mobile carriers before activation. Once the campaign is Active, you can start messaging.
