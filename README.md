# Magento 2 Product Attachments Extension

## Introduction
The **Magento 2 Product Attachments** extension by CodeDecorator allows store owners to attach files such as PDFs, images, manuals, guides, and other downloadable content to product pages. This enhances customer experience by providing additional information, improving engagement, and reducing support queries.

## How It Works
The **Magento 2 Product Attachments** extension enables merchants to easily upload and manage multiple file attachments for products. Customers can access and download these attachments directly from the product page, making it easier to provide detailed product documentation, warranty information, and user guides.

With seamless admin panel integration, store owners can upload, categorize, and assign attachments to specific products. The extension supports various file formats, ensuring maximum flexibility for eCommerce businesses.

## Key Features
- Attach multiple file types (PDFs, images, docs, etc.) to product pages.
- User-friendly admin panel for managing attachments.
- Restrict access to attachments based on customer groups.
- Secure file downloads with controlled access.

## Detailed Features

### 1. Multiple File Type Support
Easily attach PDFs, images, videos, text documents, and other file formats to product pages, giving customers more resources.

### 2. User-Friendly Management
Admin users can easily upload, categorize, and assign attachments to products via an intuitive backend interface.

### 3. Customer Group Restriction
Restrict access to product attachments based on customer groups to ensure that only the intended audience can download them.

### 4. Secure File Downloads
Ensure secure downloads by managing permissions and controlling file access.

## Extension Installation

To install the **Magento 2 Product Attachments** extension, use Composer:

### Step 1: Install the extension using Composer
```sh
composer require codedecorator/magento2-product-attachments
```
For a specific version:
```sh
composer require codedecorator/magento2-product-attachments:version
```
*Note: You may need authentication keys from the vendor or Magento Marketplace.*

### Step 2: Run Magento Commands
```sh
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How to Configure Magento 2 Product Attachments Extension

### Step 1: Navigate to the Configuration Panel
Go to **Admin Panel > Stores > Configuration > CodeDecorator > Product Attachments**.

### Step 2: Enable the Extension
Set **Enable Product Attachments** to **Yes**.

### Step 3: Upload and Assign Attachments
- Navigate to **Catalog > Products**.
- Edit a product and go to the **Product Attachments** tab.
- Upload files and set customer group restrictions if necessary.

### Step 4: Save Configuration
Click **Save Config** and refresh the cache.

## Download Our [Magento 2 Product Attachments](https://codedecorator.com/magento-2-product-attachments.html) Extension
