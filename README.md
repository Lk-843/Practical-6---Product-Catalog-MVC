# Practical 6 — Product Catalog using ASP.NET MVC

**Subject:** .NET Technologies  
**Aim:** Create a Product Catalog Application using ASP.NET MVC Architecture (Models, Controllers, Views, and Routing).

## Project structure

```text
Practical-06-Product-Catalog-MVC/
├── Models/
│   └── Products.cs
├── Controllers/
│   └── ProductsController.cs
├── Views/
│   └── Products/
│       └── productsView.cshtml
└── README.md
```

## Sample products

| ID | Name | Category | Price | Description |
|---:|---|---|---:|---|
| 101 | Laptop | Tech | 130000 | Lenovo Legion 5 Laptop with 8GB RAM, 2TB SSD |
| 102 | Mobile | Tech | 400000 | IPhone DUO. Base Model |
| 103 | A4 Book | Edu | 50 | An A4 book with ruler pages |

## How it works

- **Model (`Products.cs`):** Defines product properties.
- **Controller (`ProductsController.cs`):** Creates a list of sample products and passes it to the view.
- **View (`productsView.cshtml`):** Displays the product list in an HTML table.
- **Routing:** The controller action is `ProductsController.Index`; in a standard MVC project, open `/Products` to view the catalog.

## Run in Visual Studio

1. Create an **ASP.NET Web Application (.NET Framework)** project using the **MVC** template.
2. Use `Practical_06_Product_Catalog_MVC` as the project namespace, or update namespaces in the files to match your project.
3. Add the source files to the matching folders shown above.
4. Ensure the MVC route configuration uses the standard `{controller}/{action}/{id}` route.
5. Run the application and navigate to `/Products`.

> This ZIP contains the practical's source files and README, not a complete Visual Studio solution. Add the files to an ASP.NET MVC project to run them.
