---
id: 10dlc
slug: /
---

import Lead from "@site/src/components/Lead";

# Registering 10DLC brands and campaigns

<Lead>
  This guide explains how to register a 10DLC brand and campaign to send messages using 10-digit long codes
</Lead>

## What is 10DLC?

10DLC stands for "10-digit long codes." They're local US phone numbers (like "(555) 123-4567") that businesses use to send text messages.

Unlike short codes (like "56789") or toll-free numbers (like "1-800-555-1212"), 10DLCs look like regular local phone numbers.

Mobile carriers in the US consider all messages (SMS and MMS) sent using a messaging provider like Wavix to be Application-to-Person traffic.

To use 10DLCs as sender IDs for Application-to-Person messaging, you must register your [brand](#10dlc-brand-registration) and [campaign](#10dlc-campaign-registration) with [the Campaign Registry (TCR)](https://www.campaignregistry.com/).

:::note
You don't need to register a brand or campaign to send messages using short codes or toll-free numbers.
:::

The Wavix platform allows you to register 10DLC brands and campaigns directly from the user interface.

:::warning

Always provide up-to-date and accurate details during the registration process. The information you enter might affect message throughput.

:::

This guide uses the following Wavix gateways:

- Register your Brand
- Register your campaign and outbound numbers (aka 10DLCs or Sender IDs)

## 10DLC brand registration

Keep in mind that:

- Each brand registration must be pre-approved by mobile carriers
- Actual message throughput is determined by carriers after the registration is approved and depends on the provided brand details and actual message content

### Registration types

Depending on the legal status of your business, you can choose either **Quick** or **Standard** brand registration.

**Quick** registration is restricted to sole proprietors without an EIN or Tax ID and requires fewer brand details to be provided during the registration process. Brands selecting the Quick registration are limited to a single 10DLC phone number and have low messaging throughput.

**Standard** registration requires detailed company information and offers higher throughput. Brands can have up to fifty 10DLC campaigns, with up to forty-five 10DLC phone numbers per campaign.

:::note
Mobile carriers automatically allocate message throughput based on the submitted brand details and message content.
:::

### Registering a brand

To register a brand you need to provide complete, accurate, and up-to-date information about your organization, including:

- Brand name or DBA name
- The website address, optional for Quick brand registration
- Company legal name
- Industry or vertical the business operates in
- Country of registration
- EIN for US companies and Tax ID for companies incorporated in other countries, if applicable
- Company type, if applicable
- Stock exchange, for publicly traded companies only
- Stock symbol, for publicly traded companies only
- Contact details
- Company support email address and phone number
- The company’s business address must exactly match the legal address in the registration documents

If you’ve chosen **Quick** registration, you have to provide the contact details of the business owner. For **Standard** registration, contact details must contain the first and last name of the person filing the brand registration request.

<figure>

![registration](/img/registration.jpg)

<figcaption>Fig. 1 Brand registration</figcaption>
</figure>

After providing the information, click Next to view the brand registration summary page and check the provided details. If you need to update any of the fields, click Back to go to the previous step.

If the information is correct, confirm a non-refundable brand registration fee and click Submit.

### Brand registration status

The brand registration status is based on the accuracy of the submitted information. The Campaign Registry (TCR) Administrator will locate and confirm the existence of the Company you submitted by checking against several databases and utilizing verification software. Correct legal company name and address, EIN or Tax ID are extremely important for obtaining a ‘Verified’ status.

If your brand can not be verified, you can resubmit the form after updating the brand details.

Wavix provides feedback to help you identify possible data inaccuracies.

## 10DLC campaign registration

### Before you begin

Before registering a 10DLC campaign, you need to have an active US local phone number on your account.

### Registering a campaign

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
