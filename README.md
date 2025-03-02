# Product-review

Product Management:-
**Displaying the product details  with edit ,update,delete functionality and has stock managment and also we can place the order for product.


1:- Products:-
a:- We have created one Seperate Product Folder inside Project and inside that Product folder we have created Product.aspx page.
b:- On that Product.aspx we have taken one button of (Add Product) on click of that the product form gets opened to  put the details of product and click on submit the product detaisl get saved 
    and in gridview the product details get displayed. On cancel the products details that you filled get erased and the form get closed.

c:- Now In Gridview I have added the edit and delete button(On edit click the product form get opened when current details of product and when you chnage some details and click o update the details get updated and in gridview the product get bind with updated.(On delete click one pop up get displayed as confirm to delete product we clcik yes then product get deleted else not and the gridview get updated with removed product.

d:Added filters above the gridview as filter the product by Category,Price Range and Avalibility. When select Category and clcik on filter button the product get filter,same for price range if we put in minprice as 200 and maxprice as 400 then product get displayed with price range between 200 to 400 and Availibility where we select available then it will filter the product whiich are available based on stock avalibility.

c:- Add one button that is Place order and when click on that it redirect to order.aspx page to place order.


2:- Orders:-

a:- We have created seperate Order.aspx page as when page get loaded the place order form get opened to place order.

b:- In Place order we seleeect product and quanity of hwo much you want and then click on submit if stock is avaible then order get placed and if stock not available then it give error messsage as stock is not there.When Order get place successfully the stock get reduced from prodict table and product details get updated.

c:- Also when get order get placed the order details get shown in gridview table.


d:- We have added one button in Gridview As Give review such that if we  want to give review of particular order then on click on that button it get redirect to Reveiw.aspx Page and you can give review.

3:- Product Reviews:-

a:- For giving Product Review we have  created seperate page Review.aspx.
b:- We have created one form with review text and rating.
c:- On submit click the review get submiited and we get message with pop up of successsfull review submission and when we click on that successful revie



