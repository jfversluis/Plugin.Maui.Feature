# Plugin.Maui.Feature

The `Plugin.Maui.Feature` repository is a template repository that can be used to bootstrap your own .NET MAUI plugin project. You can use this project structure as a blueprint for your own work.

## Getting Started
1. Create your own GitHub repository from this one by clicking the "Use this template" button and then "Create a new repository". More information in the [documentation](https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template). After that, clone the repo to your local machine.

2. Replace all occurrences of `Plugin.Maui.Feature` with whatever your feature or functionality will be. For instance: `Plugin.Maui.ScreenBrightness` or `Plugin.Maui.Audio`. Of course the name can be anything, but to make it more discoverable it could be a great choice to stick to this naming scheme. You can easily do this with your favorite text-editor and do a replace all on all files.

   2.1 Don't forget to also rename the files and folders on your filesystem.

3. In the csproj file of the plugin project (under `src`), make sure that you replace all relevant values to your project. This means the author of this project, the description of the project, the target framework (.NET 7, 8 or something else). If you don't want to or can't support a certain platform, remove that target platform altogether.

4. Delete this `README.md` file and rename `README_Feature.md` to `README.md`. Fill that README file with all the relevant details of your project.

5. Check the LICENSE file if this reflects the license that you want to distribute your project under. At the very least add your name there and the current year we live in.

6. Create a nice icon in the `nuget.png` file that will show up on nuget.org and in the NuGet manager in Visual Studio.

7. Write your plugin code (under `src`) and add samples to the .NET MAUI sample app (under `samples` folder)

8. Make super sure that your package won't show up as `Plugin.Maui.Feature` on NuGet! If one does, you owe me a drink!

9. Publish your package to NuGet, a nice guide to do that can be found here.

10. Enjoy life as a .NET MAUI plugin author!

As an example of all of this you can have a look at [Plugin.Maui.ScreenBrightness](https://github.com/jfversluis/Plugin.Maui.ScreenBrightness) or [Plugin.Maui.Audio](https://github.com/jfversluis/Plugin.Maui.Audio).