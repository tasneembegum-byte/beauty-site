# Beauty Salon Website Deployed using Azure Portal

---

## 1. Logged in to Azure Portal

1. Logged into the portal using (https://portal.azure.com)

---

## 2. Created a Resource Group

1. Created a resource group through the Azure portal.
2. Provided:

   * *Subscription*
   * *Resource group name:* BeautySalonRG
   * *Region:* Central India

---

## 3. Created a Storage Account

1. Created a storage account within the portal.
2. Filled in:

   * *Subscription:* Same as resource group.
   * *Resource group:* BeautySalonRG.
   * *Storage account name:* beautysalonstorage
   * *Region:* Same as resource group region.
   * *Redundancy:* Locally-redundant storage (LRS).
   * Under data protection tab, disabled all soft delete options.

---

## 4. Enabled Static Website Hosting

1. Enabled static website hosting using the storage account.
2. Set:

   * *Index document name:* index.html
   * *Error document path:* 404.html
3. A *Primary Endpoint URL* was generated, which serves as the link to my website.

---

## 5. Downloaded and Installed Azure Storage Explorer

1. Downloaded Azure Storage Explorer from (https://azure.microsoft.com/en-us/products/storage/storage-explorer/)
2. Installed it on my Windows computer.

---

## 6. Connected Azure Storage Explorer to My Account

1. Connected Azure Storage Explorer to my Azure account using the provided credentials.

---

## 7. Uploaded Website Files

1. Uploaded all template files and folders to the blob container named `$web`.

---

## 8. Viewed the Beauty Salon Website

1. Pasted the primary endpoint URL into my browser.
2. My Beauty Salon website was successfully live and accessible via the URL.

---
