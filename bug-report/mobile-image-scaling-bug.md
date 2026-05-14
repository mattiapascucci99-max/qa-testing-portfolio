#BUG Report - Product Image Displays Incorrectly After Page Refresh on Mobile
## Bug ID
BUG-002
## Title 
Product image appears enlarged and visually distorted after page refresh on mobile device

##severity 
Medium

##Priority
Medium

##Environment
-Device: Iphone 15
-Os: IOS
-Browser: Mozilla Firefox
-Website: SauceDemo
-URL: https://www.saucedemo.com
-Network: 5G

---

##Description

After interacting with product buttons and refreshing the page, opening a product image causes the image to display with incorrect dimensions and an unpleasant visual effect on mobile view

---
##Precondition
-User logged into SauceDemo account
-Product inventory page loaded

---

##Steps to reproduce
1.log into Saucedemo using valid credentials
2.Add products to the cart using the "add to cart" buttons
3.Verify products are not duplicated inside the cart
4.Refresh page 
5.Tap on a product image
6.Observe the product image display

---

##Expected Result
The product image should maintain consistent proportions and fit correctly within the mobile layout

---

##Actual Result
The product image appears enlarged and visually disproportionate, creating an incosistent and unpleasant visual effecton the mobile interface

---

##Frequency
Occurs intermittently after refreshing the page

---

##Attachments
-Screenshot 1: normal product layout
-Screenshot 2: enlarge/distorted image after refresh

---

##Notes
The issue may be related to responsive image scaling or mobile rendering after page refresh
