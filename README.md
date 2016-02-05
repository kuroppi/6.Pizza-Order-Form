Pizza Order Form

Part 1 – Delivery Location

A form that allows the user to enter their personal information and to build a pizza for delivery online.


- The address type is a drop down list that contains options for house, apartment, business, campus, hotel, dorm, or other. 
- If the user selects other, an additional text box programmatically appears that allows the user to freely enter the “other” address type. If anything other than “other” is selected, the text field will not be visible.
- Using pure JavaScript, it will validate and ensure that the user enters a value (or makes a selection) for each of the form items here.
- Regular expressions are used to ensure that their name doesn’t contain any numbers and that their zip code, phone number, and email address are formatted correctly.
- The user may only enters two alpha characters in the state field.

Part 2 – Build Your Order

A radio button group that includes the 4 dough options listed here:

- Hand Tossed 
- Thin Crust 
- New York Style
- Gluten Free

STEP 2: Depending on which dough option the user selects, a drop down menu that contains the size and cost of the pizza will be programmatically populated based on the options below: 

- If Hand Tossed Selected: Small ($9.99), Medium ($12.99), Large ($14.99) 
- If Thin Crust Selected: Medium ($11.99), Large ($13.99)
- If New York Style Selected: Large ($16.99), Extra Large ($19.99)
- If Gluten Free Selected: Small ($10.99)

STEP 3: Add a drop down list for cheese options with these options:

- Light: no charge
- Normal (default): no charge
- Extra: +$2.99
- Double: +$3.99

STEP 4: A drop down list for sauce options, populated with these options:

- Regular Tomato: no charge (default)
- Hearty Tomato: +$.99
- BBQ Sauce: +$1.99

STEP 5: A checkbox group of options for toppings. Each topping is $.99 extra for the following toppings: pepperoni, sausage, ham, bacon, salami, peppers, olives, jalapenos, mushrooms, pineapple, and onion. A checkbox list is used here so the user can select more than one option.

- A running total of the user's order is in the upper right hand corner of the page, updated dynamically.
- A "Finished Building Pizza" button is at the bottom of the page.  When clicked, a confirmation box will appear. 

Part 3 – Billing Information

- The user can enter a series of fields similar to the fields in Part 1.
