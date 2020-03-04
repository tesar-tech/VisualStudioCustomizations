# Visual Studio Customizations

## Item templates

This is how to create new item template: 

- https://docs.microsoft.com/en-us/visualstudio/ide/how-to-create-item-templates?view=vs-2019
- https://www.intertech.com/Blog/creating-visual-studio-project-templates-and-item-templates/

This repo contains item template for view model using mvvm light (`ViewModel.zip` file). It will generate something like this: 

``` csharp
using GalaSoft.MvvmLight;
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

### Default templates

 For inspiration, default templates are located here: `C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\Common7\IDE\ItemTemplates\CSharp\Code\1033` (e.g. Class template)
