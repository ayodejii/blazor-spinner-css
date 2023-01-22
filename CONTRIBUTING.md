# Contributing Guidelines

### How to add your own spinner?
1) Fork and clone the project.
2) Create your spinner: `YourSpinner.razor` component in the [components folder](src/BlazorSpinner/Component).
3) Add the corresponding style sheet `YourSpinner.razor.css`.
4) Add your spinner to the demo pages (blazor web assembly and blazor server) in `test/BlazorAppTest/Pages/Index.razor`, and `test/BlazorServerAppTest/Pages/Index.razor`.
5) Add your spinner to the list of spinners table in the [README](README.md) file.
6) Share with the community by submitting a PR.

### How to update or add features?
1) Fork and clone the project.
2) Update the code or add your features.
3) Run the project to see that your update is working correctly.
4) Update the parameters in the spinners table if needs in the [README](README.md) file.
5) Share with the community by submitting a PR.
