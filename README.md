# Test suite for JPetStore

This repo has test cases for https://petstore.octoperf.com/actions/Account.action. I used it as a prod environment. As far as this link has multiple issues (see the spreadsheet) I also run Petstore app locally from https://github.com/mybatis/jpetstore-6.

Test-suite covers the following functions:

1. Sing in
2. User registration
3. Adding item to cart
4. Checkout

**Testing Environment:** Microsoft Windows 10 Pro, Google Chrome 96.0.4664.45 (64 bit)

UI tests can be found in _test-suite JPetStore.xlsx_

Postman collection for JPetsore API is in _JPetStore.postman_collection.json_

Running JPetStore sample under Tomcat (using the cargo-maven2-plugin).

Clone this repository

$ git clone https://github.com/mybatis/jpetstore-6.git
Build war file

$ cd jpetstore-6
$ ./mvnw clean package -DskipTests