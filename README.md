# Permate Brand SuperTag - Google Tag Manager

The SuperTag Template by Permate supports the standard Google Tag template and is a JavaScript library containing all the functions/features necessary for Permate's tracking solution. The Permate SuperTag should be placed on every page that needs tracking, except for the thank you/payment confirmation page. On the thank you/payment confirmation page, please choose to integrate the [Permate Conversion Tag](https://github.com/permate-tech/permate-conversion-tag-template-gtm) instead.

## Integration Document Overview

<ol>
  <li>Install the Permate SuperTag into your Tag list.</li>
  <li>Install Custom HTML.</li>
  <li>Advanced configuration of the Permate SuperTag.</li>
</ol>

## 1. Install the Permate SuperTag

<ol>
  <li>Log in to your Google Tag Manager account, select the corresponding Account/Container, then go to <b>Tags</b> and click on <b>New</b>.</li>
  <li>Click on <b>Tag Configuration</b>.</li>
  <li>Select the option <b>Discover more tag types in the Community Template Gallery</b>.</li>

  ![GTM_SuperTag_discover](https://github.com/user-attachments/assets/50283868-b229-4b76-96f7-d56e0f3285b3)
  <li>Search for the phrase <b>"permate supertag"</b>, then add the Tag to your workspace.</li>

  ![GTM_SuperTag_search](https://github.com/user-attachments/assets/995b2549-a237-4c5e-8cd6-a0eac63e3941)
  <li>This tag will need to use a Trigger that activates all <b>DOM Ready</b> events.</li>
  
  ![GooogleTagManager_Trigger](https://github.com/user-attachments/assets/0cb3bff8-9490-4eec-b161-7637714b684c)
  <li>Name your tag, and everything is complete.</li>
</ol>

## 2. Install Custom HTML

<ol>
  <li>Log in to your Google Tag Manager account, select the corresponding Account/Container, then go to <b>Tags</b> and click on <b>New</b>.</li>
  <li>Click on <b>Tag Configuration</b>.</li>
  <li>Under the <b>Custom</b> section, select <b>Custom HTML</b>.</li>

  ![GTM_CustomHTML_View](https://github.com/user-attachments/assets/e085a442-ab8f-4925-91c8-2daa39218c7b)
  <li>In the <b>HTML</b> section, you need to insert the JavaScript code from the file <a href="https://github.com/permate-tech/permate-supertag-template-gtm/blob/main/customScript.html"><b>customScript.html</b></a> here.</li>

  ![GTM_CustomHTML_Value](https://github.com/user-attachments/assets/ea7faeaf-45a5-411c-94e6-68753d12746e)
  <li>This tag will need to use a Trigger that activates all <b>DOM Ready</b> events, similar to the <b>Permate SuperTag</b>.</li>
  
  ![GooogleTagManager_Trigger](https://github.com/user-attachments/assets/0cb3bff8-9490-4eec-b161-7637714b684c)
  <li>Name your tag, and everything is complete.</li>
</ol>

## 3. Advanced Configuration for the Tag
  
<ol>
  <li>Log in to your Google Tag Manager account, select the corresponding Account/Container, go to <b>Tags</b>, then select the <b>Permate SuperTag</b> that was created in step 1.</li>
  <li>Click on <b>Advanced Settings</b>.</li>
  <li>In the <b>Tag firing priority</b> section: You need to enter a value greater than the value of the <b>Permate Button Tag</b> (if it exists).</li>

  ![GTM_Permate_SuperTag_Priority](https://github.com/user-attachments/assets/a1d452c2-3e95-4071-99f6-ae12930db198)
  <li>Click <b>Save</b>.</li>
  <li>Select the <b>Custom HTML</b> tag that was just created in step 2.</li>
  <li>Click on <b>Advanced Settings</b>.</li>
  <li>In the <b>Tag firing priority</b> section: You need to enter a value greater than the Tag firing priority value of the <b>Permate SuperTag</b>.</li>

  ![GTM_Permate_CustomHTML_Priority](https://github.com/user-attachments/assets/142cd081-6fa5-4071-ad46-5c23ebe44e35)
  <li>Click <b>Save</b>, and everything is complete.</li>
</ol>

## Learn more details about Permate SuperTag
#### :arrow_right: Visit here [Help Center](https://permate.com/docs-category/brand-en/)
