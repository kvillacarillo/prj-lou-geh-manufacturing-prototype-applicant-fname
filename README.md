

## **Lough Geh Manufacturing Company**
Lou Geh manufacturing company produces products. The following product informationis stored: product name, product ID and quantity on hand. These products are madeup of many components. Each component can be supplied by one or more suppliers. Thefollowing component information is kept: component ID, name, description, suppliers who supply them, and products in which they are used.

- A supplier can exist without providing components.
- A component does not have to be associated with a supplier.
- A component does not have to be associated with a product. Not all components are usedin products.
- A product cannot exist without components.


### **Task**
1. Create a prototype based on the attached problem
2. Technologies and design to be used are the following:
    * Backend approach - REST -API
    * API Backend -  NodeJS
    * Database - MySQL
    * Frontend - Basic HTML, CSS and Javascript
3. As for your application documentations you need to provide the ff:
   1. ERD
   2. DFD
4. The application should be published in Github (in this repository) with Read Me containing the setup guide
5. You will send the Github link to us thru our email devops@biotechfarms.com on or before **[DATE OF SUBMISSION]**

### **Submission format**
- Github repository should follow the name convention: ```prj-lou-geh-manufacturing-prototype-<APPLICANT-NAME>```.
- Repository should show codebase directory directly **DO NOT PUT YOUR CODE BASE IN A ZIP FILE** use git commands instead to push your code-base and further updates.
- Prototype's latest version should be the default branch of the repository.
- Provide a READ.ME file on how to install and deploy your prototype, and its prerequisite, software, sdk(if needed), and driver.


### **Directory structure**
    my-rest-api/
    ├── node_modules/                  (Generated by npm/yarn)
    ├── controllers/                   (For handling routes and business logic)
    │   ├── userController.js
    │   ├── productController.js
    │   └── ...
    ├── models/                        (For defining data models)
    │   ├── userModel.js
    │   ├── productModel.js
    │   └── ...
    ├── routes/                        (For defining API routes)
    │   ├── userRoutes.js
    │   ├── productRoutes.js
    │   └── ...
    ├── middleware/                    (Custom middleware functions)
    │   ├── authMiddleware.js
    │   └── ...
    ├── config/                        (Configuration files)
    │   ├── database.js
    │   ├── env.js
    │   └── ...
    ├── utils(Optional)/               (Optional utility functions)
    │   ├── validation.js
    │   └── ...
    ├── provisions
    |   └── database.sql                (Database backup)
    ├── app.js                          (Main application entry point)
    ├── package.json                    (Dependency configuration)
    ├── package-lock.json               (Generated by npm)
    └── README.md                       (Project documentation)
    ========================================================================
    my-front-end-app/
    ├── node_modules/        (Generated by npm/yarn)
    ├── js/
    |   └── app.js           (Javascript scripts)
    ├── css/
    |   └── style.css        (CSS scripts)
    ├── index.html           (Entry point)
    └── README.md            (Project documentation)
