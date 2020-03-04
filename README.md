# Visual Studio Customizations

## Item templates

This is how to create new item template: 

- https://docs.microsoft.com/en-us/visualstudio/ide/how-to-create-item-templates?view=vs-2019
- https://www.intertech.com/Blog/creating-visual-studio-project-templates-and-item-templates/

This repo contains item template for view model (`ViewModel.zip` file). It will generate something like this: 

``` csharp
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace MyNamespace
{
    public class MyViewModel : ViewModelBase
    {
    }
}
```

### How to import template

Open `%USERPROFILE%\Documents\Visual Studio 2019\Templates\ItemTemplates` and paste the zip file. Reopen VS.
