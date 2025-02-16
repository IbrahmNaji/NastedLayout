Project Objective
Divide the design into reusable sections such as Header, Footer, and Sidebar.
Use a main layout that contains a sub-layout

Tools & Techniques Used
ASP.NET Core MVC
Razor Views & Layouts

 Structure:
 
/Views/Shared/
│── _MainLayout.cshtml // Main layout
│── _SubLayout.cshtml // Nested layout for some pages
│── _Header.cshtml // Header
│── _Footer.cshtml // Footer
│── _Sidebar.cshtml // Sidebar
│── Home/
│ ├── Index.cshtml // Home page
│ ├── About.cshtml // About us page
