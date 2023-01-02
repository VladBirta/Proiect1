# Test Cases

Below are some Test Cases that I did while working on some projects

--------------------

**Title:**
Test login with correct credentials

**Description:**
Test the login by using correct credentials.

**Steps to reproduce:**

1. Go to site.com/login
2. Add correct user/pass
3. Press the login button


**Expected result:**
User should be able to login

**Test data:**
User: test Pass: 123

--------------------

**Title:**
Negative test with symbols

**Description:**
Test the login by using the hastag symbol multiplied

**Steps to reproduce:**

1. Go to site.com/login
2. Add hashtag in the username field
3. Press the login button


**Expected result:**
The login functionality should not work.


**Test data:**
User: ####### Pass: #######

--------------------

**Title:**
"Other testing" logging in with no credentials

**Description:**
Test the login by not filling the credential fields.

**Steps to reproduce:**

1. Go to site.com/login
2. Do not add any information in the fields
3. Press the login button

**Expected result:**
The login functionality should not work.

**Test data:**
User: ####### Pass: #######

--------------------

**Title:**
Test Remember me checkbox.

**Description:**
Test the check box if it keeps the user logged in.

**Steps to reproduce:**

"1. Go to site.com/login
2. Add correct credentials
3. Tick the box
4. Log in
5. Close the app"

**Expected result:**
The user should be logged in automatically, 
when accessing the app.

**Test data:**
User: test Pass: 123

--------------------

**Title:**
Test search bar if it works properly

**Description:**
Test the search bar if it works in desplaying the desired products

**Steps to reproduce:**

"1. Go to www.emag.ro
2. Add a name product in the search bar
3. Click the ""Search"" button

**Expected result:**
It should desplay the product that the user typed in the bar

--------------------

**Title:**
Autocompletion of the text in the search bar

**Description:**
Type a product in the search bar.

**Steps to reproduce:**

1. Go to www.emag.ro 
2. Type a word in the search bar 

**Expected result:**
It should list choices based on the typed word.

--------------------

**Title:**
Test search bar for non-existent products

**Description:**
Type a product that doesn not exist, in the search bar.

**Steps to reproduce:**

"1. Go to www.emag.ro 
2. Type a product in the search bar, that doesn not exist"

**Expected result:**
It should desplay a message, which claims that the product does not exist.
