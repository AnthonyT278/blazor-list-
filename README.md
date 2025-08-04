Create a todo list Blazor app project
Modify Razor components
Use event handling and data binding in components
Use routing in a Blazor app


dotnet new blazor -o TodoList
The -o|--output option creates a folder for the project. If you've created a folder for the project and the command shell is open in that folder, omit the -o|--output option and value to create the project.

cd TodoList
dotnet new razorcomponent -n Todo -o Components/Pages
The -n|--name option in the preceding command specifies the name of the new Razor component. The new component is created in the project's Components/Pages folder with the -o|--output option.


