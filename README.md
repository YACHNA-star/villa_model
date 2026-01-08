# Asset-Management-System
Clean Architecture (ASP.NET Core MVC)
## Routing
<img width="618" height="319" alt="image" src="https://github.com/user-attachments/assets/da81465c-e11c-430b-8be1-bca5da8b32af" />

### Default route
The default route template "{controller=Home}/{action=Index}/{id?}" maps most URL's that have the following pattern example

http://localhost:1234/Employees/Details/1

<img width="437" height="145" alt="image" src="https://github.com/user-attachments/assets/c2351af1-0558-4908-8b2d-3a51aa9adc3b" />

## Default view

<img width="602" height="758" alt="image" src="https://github.com/user-attachments/assets/7c53b111-c72e-4f3b-bf22-99965c93b219" />

### default view

 _ViewStart.cshtml in the Views folder sets the Layout property to "~/Views/Shared/_Layout.cshtml". So, the _layout.cshtml would be a layout view of all the views included in Views and its subfolders.

 ### we can hange default view
  _ViewStart.cshtml in the Home folder sets the Layout property to _myLayoutPage.cshtml. So now, Index.cshtml, About.cshtml and Contact.cshtml will display in the _myLayoutPage.cshtml instead of default _Layout.cshml.


