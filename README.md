# React Spinners CSS Loaders ([React](https://github.com/JoshK2/react-spinners-css), [Vue](https://github.com/JoshK2/vue-spinners-css), [Angular](https://github.com/JoshK2/ng-spinners))

[![Nuget version](https://img.shields.io/nuget/v/blazor-css-spinner)](https://www.nuget.org/packages/blazor-css-spinner)
[![Nuget Downloads](https://img.shields.io/nuget/dt/blazor-css-spinner?color=orange)](https://www.nuget.org/packages/blazor-css-spinner)

![blazor_css_updated](https://github.com/ayodejii/blazor-spinner-css/assets/43586181/9c569226-8ffe-40d1-8684-f9bc2792f465)

> This library requires the .NET 7 SDK.

Amazing collection of Blazor spinners components with pure css.  
The Blazor spinners are based on [loading.io](loading.io) and from all over the web.  
If you want to add your own spinner, please follow the [contributing guidelines](CONTRIBUTING.md).

- 💅No extra CSS imports
- ✂️Zero dependencies

## 🚀 List of Spinners - Parameters and their types

The following components accept a `Color` parameter, and few also accept a `Size` parameter.  
The default `Color` parameter is `#7f58af`.  
Components that accept `Size` parameter have a default size in pixel.

| Spinner        | Color: string | Size: int    | 
|----------------| ------------- | ------------ |
| `<Circle/>`    | `#7f58af`     | `64`         | 
| `<Default/>`   | `#7f58af`     | `80`         | 
| `<Ellipsis/>`  | `#7f58af`     | `80`         |
| `<DualRing/>`  | `#7f58af`     | `80`         |
| `<Facebook/>`  | `#7f58af`     | `80`         | 
| `<Grid/>`      | `#7f58af`     | `80`         | 
| `<Heart/>`     | `#7f58af`     | `80`         | 
| `<Hourglass/>` | `#7f58af`     | `32`         |
| `<Ring/>`      | `#7f58af`     | `80`         | 
| `<Ripple/>`    | `#7f58af`     | `80`         | 
| `<Roller/>`    | `#7f58af`     | -            | 
| `<Spinner/>`   | `#7f58af`     | -            |
| `<Orbitals/>`  | `#7f58af`     | -            | 
| `<Ouroboro/>`  | `#7f58af`     | -            |
| `<Ball/>`      | `#7f58af`     | `80`         |
| `<CubeGrid/>`  | `#7f58af`     | `80`         |

The following components accept three parameters, `PrimaryColor`, `SecondaryColor`, and a `Size` parameter.
The default `PrimaryColor` and `SecondaryColor` parameter values are `#7f58af` and `#88AF58` respectively.
Components that accept `Size` parameter have a default size in pixel.

| Spinner        | PrimaryColor: string | SecondaryColor: string | Size: int | 
|----------------|----------------------|------------------------|-----------|
| `<Disk/>`      | `#7f58af`            | `#FC94AF`              | `80`      | 
| `<DualBall/>`  | `#7f58af`            | `#FC94AF`              | `80`      |
| `<PivotBall/>` | `#7f58af`            | `#FC94AF`              | `80`      |

Add the package to your application using dotnet cli

```
  dotnet add package blazor-css-spinner --version 1.0.2
``` 
using dotnet CLI

## Usage Examples

```
<Circle /> @default color is #7f58af@
<Circle Color="red" />
<Circle Color="#be97e8" Size=200 /> @size parameter is int in pixel@
<Heart Color=GetRandomColor() />

@code
{
    string GetRandomColor() => "red";
}
```
