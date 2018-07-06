# Sitecire Project Setup

### Used Versions
    01. sitecore 9 update 1
    02. visual studio 2017
    03. TDS 5.7
    04. Unicorn 

### Set up of the siteore steps(First complete installing a sitecore instance):
    01. Create empty MVC ASP.NET project
    02. Copy web.config and replace the project's one with the sites web.config
    03. Add a new Neuget Source. the link is,
        ```
            NuGet V3 feed URL (Visual Studio 2015+)
            https://sitecore.myget.org/F/sc-packages/api/v3/index.json
        ```
    04. Install sitecore nuget packages,
        > sitecore.kernel
        > sitecore.MVC
        > sitecore.MVC.Analytics
    05. in views > web.config file add these  in the namespace section
        ```
            <add namespace="Sitecore.Mvc" />
            <add namespace="Sitecore.Mvc.Presentation" />
        ```
    06.  publish

### References:
    01. [sitecore 9 installation guide](https://doc.sitecore.net/sitecore_experience_platform/developing/developing_with_sitecore/set_up_sitecore_and_visual_studio_for_development) 
    02. [sitecore nuget package link](https://doc.sitecore.net/sitecore_experience_platform/developing/developing_with_sitecore/sitecore_public_nuget_packages_faq)
