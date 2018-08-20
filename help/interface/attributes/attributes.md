---
description: Overview and prerequisites about uploading customer attributes to the Experience Cloud.
keywords: core services;customer attributes
seo-description: Overview and prerequisites about uploading customer attributes to the Experience Cloud.
seo-title: Customer attributes
solution: Experience Cloud
title: Customer attributes
uuid: 02814fb1-2916-4677-a057-ee13d6686b02
index: y
internal: n
snippet: y
translate: y
---

# Customer attributes

**[!UICONTROL  People]** > **[!UICONTROL  Customer Attributes]** 

If you capture enterprise customer data in a customer relationship management (CRM) database, you can upload the data into a customer attribute data source in the Experience Cloud. Once uploaded, leverage the data in [!DNL  Adobe Analytics] and [!DNL  Adobe Target]. 

![](assets/custom_reports.png) 

Topics covered on this page: 

* [ Prerequisites for uploading Customer Attributes](../attributes/attributes.md#section_BD38693AFBF34926BA28E964963B4EA0)
* [ What Is enterprise customer data?](../attributes/attributes.md#section_6F34C29F11414842AA57D2B1248FA3C6)
* [ Solution use cases](../attributes/attributes.md#section_4E77650F6CEE4C4ABCD0B3221A5AE5D9)

## Prerequisites for uploading Customer Attributes {#section_BD38693AFBF34926BA28E964963B4EA0}


* **Solution enablement:** [ Enable your solutions for core services](../core_services/core_services.md#concept_07ED1D5C64234E77976E6D572E78FB9C). 

* **Group membership:** To upload customer attribute data, users must be members of the [ Customer Attributes group](../admin_getting_started/admin_getting_started.md#task_3295A85536BF48899A1AB40D207E77E9). You must also belong to either an Adobe Analytics group or an Adobe Target group. 

  To know whether your company has access to customer attributes, your [!DNL  Experience Cloud] administrator should log into the [!DNL  Experience Cloud]. Navigate to **[!UICONTROL  Administration]** > **[!UICONTROL  Launch Admin Console]** > **[!UICONTROL  Groups]**. If *` Customer Attributes`* displays as one of the groups, you are ready to begin. 

  Users that are added to the Customer Attributes group will see the [!UICONTROL  Customer Attributes] menu item on the left side of the Experience Cloud interface. 

* **Target mbox:** mbox.js version 58 or higher is required for customer attributes. 

  See [ Mbox.js Implementation](https://marketing.adobe.com/resources/help/en_US/target/ov/t_mbox_download.html). 

* ** at.js:** Any version.


## What Is enterprise customer data? {#section_6F34C29F11414842AA57D2B1248FA3C6}

Enterprise data resides in other systems. It can be complex and mean different things to different people. This data can include information such as memberships, loyalty level, age, gender, products owned, interests, and Lifetime Value. 

The following image is an example of a data file showing subscriber data for products, including member IDs, entitled products, most-launched products, and so on. 

![](assets/01_crs_usecase.png) 

After you create the data file, you can upload it to the customer attribute source that you create in **[!UICONTROL  Experience Cloud]** > **[!UICONTROL  Customer Attributes]**. 

See [ Upload Customer Attribute Data](../attributes/t_crs_usecase.md#task_BCC327B2A0EF4A1BBB2934013AB92B78) to learn this workflow. 

## Solution use cases {#section_4E77650F6CEE4C4ABCD0B3221A5AE5D9}

After the data resides in the Experience Cloud, you can customize it and share it to solutions for reporting, segmentation, activities, and campaigns. 

For example: 

<table id="table_23FD754F93724FB9B4D32275B0AAE4F5"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Solution </th> 
   <th colname="col2" class="entry"> Advantages and Use Cases </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> Adobe Analytics </td> 
   <td colname="col2"> <p>Marketers and analysts can understand: </p> 
    <ul id="ul_3B4037784B454CD892942E814A19A606"> 
     <li id="li_382C91A24DCD49DEAC61F20BC793712B">The online campaigns that are most effective with your gold-level customers. </li> 
     <li id="li_8E0EB3432B4D4AA8987D1A10FBE1E1CA">The products that gold-level customers search for versus products that platinum-level customers search for. </li> 
     <li id="li_7C21BD089ACA42BFA478702A4D92F370">Whether your site redesign is having a positive impact on conversion rates for older customers. </li> 
     <li id="li_6F49791C95B140228C5558CFCF9334FD">Which products do customers with a low lifetime value tend to research on my site. </li> 
    </ul> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Adobe Target </td> 
   <td colname="col2"> <p>Attribute data enables Target users to: </p> 
    <ul id="ul_FA1149C892DC40B9A905BD0CFA6DE8B4"> 
     <li id="li_C957DB5DD27F4B9BB8498501285A280B">Show loyalty club members special discounts and offers. </li> 
     <li id="li_1ED3D423718F455799833BB92392FC0D">Recommend more expensive products to your luxury customers. </li> 
     <li id="li_ABBDA6236103438799BB8B820AB5EF68">For customers who already receive emails, show an upsell offer in the space normally reserved for email signups </li> 
    </ul> </td> 
  </tr> 
 </tbody> 
</table>

The following topics describe how to upload and validate customer attribute data. 