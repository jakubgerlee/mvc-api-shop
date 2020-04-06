# mvc-api-shop

MVC API w .NET 4.7 
- Hosted in  IIS (or Express)
a. Action:
	-AddToCart(productId, product) - as an input productId and amountOfProduct to add (float number).
					
	-RemoveFromCart(int productId) - input productId to remove.
	-GetCart() - pobiera zawartość koszyka - zwraca słownik <produkt ID, ilość>
	-GetAmountOfLastCart() - return amount of last cart.
				1. If amount of product is higer than 10 then price is 10zl per unit
				2. If amount of product is lower than 10 then price per unit is 5zl
				3. Amount of cart is equal of all product - amountOfProduct*price
				
				
b. Use MS SQL/sqlite with ORM
c. Add unit test xUnit. with libray Bogus or FakeItEasy
