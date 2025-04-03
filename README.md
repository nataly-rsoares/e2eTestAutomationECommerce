# e2eTestAutomationECommerce
Create an end-to-end test automation suite using Cypress for an E-commerce website
Tests:
1.Login
  a.Valid login.
  b.Invalid login.
  c.Locked out user.
2.Logout
  a.Logout from the user.
  b.Check that clicking back does not load user info.
3.Product page
  a.Verify product listing.
  b.Verify sorting by price.
  c.Verify sorting by alphabetical order.
  d.Verify by requeriments that the page has all the elements.
  e.Verify that all products have price, photo, description and add to cart button.
  f.Verify product detail when clicked.
4.Cart
  a.Add a product to the cart.
  b.Remove the product from the cart.
  c.Cart persistency.
  d.Add more then one product.
  e.Add all products.
5.Checkout
  a.Proceed to checkout.
  b.Fill out the checkout form, valid info.
  c.Fill out the checkout form, invalid info.
  d.Order confirmation.
5.Workflow
  a.Check the whole workflow, from login to finish shopping to logout.
6.Performance (Basic)
  a.Page load performance.
  b.API response time.
  c.Resource load time.
  d.Time to First Byte.
  e.Different Network response.
  f.Multiple users 
7.Security (Basic) -> Ideally its done CI Pipeline
  a.Authentication and Authorization.
  b.SQL injection and XSS tests.
  c.Session management.
  d.Security headers.
  
