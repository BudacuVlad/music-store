# 1. define objective
    Buy products from various heavy metal artists.
    Products like albums, EP's, singles, accesories, clothes.
    Find information about some artists.
# 2. define entities

## user
    user can have multiple products
    user can have multiple donations
    
## admin
    admin can have multiple users
    admin can have multiple products
    admin can have multiple artists

## artist
    artist can have multiple products

## product
    product can have multiple users

    product can be filtered by name, genre, year, details, stocks

## cart
    cart can have multiple products

##donation
    donation can have multiple users

# 3. create epics
    - user
    - products
    - artists
    - donations
    - cart

# 4. create backlog

## landing page
- view possible actions (described)
- register, login button, admin button

## admin page
- authenticate with email and password
- view admin page
- view users, products and artists list
- CRUD products and artists detail
- view donation list
- set estimated time delivery of product
- view product track

## register and login pages
- view register page
- register with email and password
- login with email and password
- logout

## forgot password
- view forgot password page
- reset password

## home page
- view home page

## donation page
- view donation page
- select amount of donation

## manage products
- view products list
- view product details
- add product in cart
- track product (shipped/delivered)

## manage user
- view user list
- update user info
- make donations for admin support

## cart
- view cart page
- view selected product list by user
- add info of order
- view estimated time delivery

