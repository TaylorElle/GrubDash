# GrubDash

Grubdash RESTful API project for applying knowledge of RESTful APIs and state management using Express.


**Tasks**

In the src/dishes/dishes.controller.js file, add handlers and middleware functions to create, read, update, and list dishes. Note that dishes cannot be deleted.

In the src/dishes/dishes.router.js file, add two routes: /dishes and /dishes/:dishId. Attach the handlers (create, read, update, and list) exported from src/dishes/dishes.controller.js.

In the src/orders/orders.controller.js file, add handlers and middleware functions to create, read, update, delete, and list orders.

In the src/orders/orders.router.js file, add two routes: /orders and /orders/:orderId. Attach the handlers (create, read, update, delete, and list) exported from src/orders/orders.controller.js.

Anytime you need to assign a new id to an order or dish, use the nextId function exported from src/utils/nextId.js

**Project rubric**
All tests are passing in Qualified.
All middleware and handler functions have a single responsibility and are named functions.
All data passed between middleware and handler functions uses response.locals.
All chained method calls on a route(...) end with all(methodNotAllowed).
All update handlers guarantee that the id property of the stored data cannot be overwritten.
