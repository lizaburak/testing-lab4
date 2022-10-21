## Functional Test Cases

[Znwr](https://znwr.ru/)

## Test Case 1

**ID:** AIB-1

**Summary:** Adding item to the bag.

**Preconditions:**

- Website https://znwr.ru/ is opened.
- All possible popups are closed.
- Item _"Mentor" coat_ is opened.

**Test steps:**

1. Select the first available size.
2. Click the "Add to Bag" button.

**Expected Result:** Added to bag popup is opened. The inscription "PRODUCT ADDED TO BAG" and the button "Checkout" are displayed here. Item is added to the bag.

**Status:** Success.

## Test Case 2

**ID:** DIB-1

**Summary:** Deleting item from the bag.

**Preconditions:**

- Website https://znwr.ru/ is opened.
- All possible popups are closed.
- Item _"Mentor" coat_ is in the bag.
- Bag page is opened.

**Test steps:**

1. Click on the trashcan icon for item.

**Expected Result:** The message "Your bag is empty" in section _4.The contents of the order_ appeared on the bag page.

**Status:** Success.

## Test Case 3

**ID:** CTSB-1

**Summary:** Calculating total sum in the bag.

**Preconditions:**

- All possible popups are closed.
- Item _"Marlen" raincoat_ is in the bag (quantity: 1).
- Item _"Garson" palazzo trousers_ is in the bag (quantity: 1).
- Bag page is opened.

**Test steps:**

1. Click the "+" sign next to the _"Marlen" raincoat_ item so that the quantity value is 2.

**Expected Result:** "Total" is equal to the sum of items' prices in the bag (1520 BYN)

**Status:** Success.

## Test Case 4

**ID:** VPW-1

**Summary:** Viewing page Women.

**Preconditions:**

- Website https://znwr.ru/ is opened.
- All possible popups are closed.

**Test steps:**

1. Click on the Women title in the header.

**Expected Result:** Women page is opened. The page contains blocks of women's clothing products, filters, header & footer.

**Status:** Success.

## Test Case 5

**ID:** VWAC-1

**Summary:** Viewing Women's Accessories category.

**Preconditions:**

- Website https://znwr.ru/ is opened.
- All possible popups are closed.

**Test steps:**

1. Hover over the category of women and in the drop-down list click on Accessories.

**Expected Result:** The women's accessories page is open. The page contains blocks of women's accessories products, filters, header & footer.

**Status:** Success.

## Test Case 6

**ID:** SP-1

**Summary:** Sorting the products.

**Preconditions:**

- Website https://znwr.ru/ is opened.
- All possible popups are closed.
- Sort is not selected.

**Test steps:**

1. Open the Women page.
2. Click on the Sort by button.
3. Click on the Popular.

**Expected Result:** All products are displayed from the most popular to the least popular, the selected option appears in the sorting block.

**Status:** Success.

## Test Case 7

**ID:** ISD-1

**Summary:** Invalid search data.

**Preconditions:**

- Website https://znwr.ru/ is opened.
- All possible popups are closed.

**Test steps:**

1. Click on the search input and type _hxdfvdbhj_ text

**Expected Result:** The message "Sorry, nothing was found for your search query".

**Status:** Success.

## Test Case 8

**ID:** CSD-1

**Summary:** Correct search data.

**Preconditions:**

- Website https://znwr.ru/ is opened.
- All possible popups are closed.

**Test steps:**

1. Click on the search input and type _Платье_ text

**Expected Result:** The product search page opens.

**Status:** Success.

## Test Case 9

**ID:** CH-1

**Summary:** Currency change.

**Preconditions:**

- Website https://znwr.ru/ is opened.
- All possible popups are closed.

**Test steps:**

1. Click on the button in the footer with the name of the BYN currency and select the name of the USD currency in the drop-down list.

**Expected Result:** Prices on the site will be presented in USD currency.

**Status:** Success.

## Test Case 10

**ID:** CIC-1

**Summary:** Change item color.

**Preconditions:**

- Website https://znwr.ru/ is opened.
- All possible popups are closed.
- Item _"Mentor" coat_ is opened.

**Test steps:**

1. Choose black from the available colors.

**Expected Result:** The coat images will change to images where the coat is shown in black. The selected color will be black.

**Status:** Success.

## Test Case 11

**ID:** WPAU-1

**Summary:** Viewing page About us.

**Preconditions:**

- Website https://znwr.ru/ is opened.
- All possible popups are closed.

**Test steps:**

1. Click on the burger menu icon.
2. Select "About Us" from the menu.

**Expected Result:** About us page is opened. The page contains brand information, header & footer.

**Status:** Success.

## Test Case 12

**ID:** MCUB-1

**Summary:** Making the checkout using the bag.

**Preconditions:**

- Website https://znwr.ru/ is opened.
- All possible popups are closed.
- At least one clothing is added to the bag.

**Test steps:**

1. Click on the bag icon in the header.
2. Fill in all required fields : Country: Беларусь, Location: Минск, Street: пр. Независимости, House: 4, Apartment: 5, Full name: Бурак Елизавета Евгеньевна, Phone: +375296574378, Email: absd@gmail.com

**Expected Result:** Information about the order will appear (order amount, delivery, total, payable). A Proceed to Checkout button will appear.

**Status:** Success.

## Test Case 13

**ID:** ISDO-1

**Summary:** Invalid emal data for order.

**Preconditions:**

- Website https://znwr.ru/ is opened.
- All possible popups are closed.
- At least one clothing is added to the bag.
- Bag page is opened.

**Test steps:**

1. In the email field, enter "xsdhkgbsk".

**Expected Result:** The email input is highlighted in red. The message "Please fill in all required fields to proceed with your order" will appear.

**Status:** Success.
