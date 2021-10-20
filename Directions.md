Classes: At least Kiosk.java and Printer.java
Kiosk (main)
	user interface - you will welcome customer, offer items for sale
			and publish unit/item prices				
	5 inventory items - should have at least five items for sale
			different prices for each (should vary)
			names or description of items should not be same length
	no more than 9 of each item can be sold
	no item price greater than 99.99
	when they are ready to check out...
	'send' to printer
	for this implementation - do not worry about how to pay, 
			or need to make change

Printer (2nd class)
40char output width is the limitation of printer
Printer uses monospace/courier font 
	- where each letter/space/character all same width
	- if handwritten, you may use underscore ( _ ) to show spacing
Tab 4 spaces 
Header (May include store name, etc)
Qty	Description/Name		Price
1	cup of soup		$ 5.99
2	briskets			$13.99

		    Subtotal     $19.98
		    Tax 7%       $ 1.77
		    Total	$xx.xx
