`nuget list -Source "http://ecclefechan.indigovision.com/nuget"`
- lists all the nuget packages (latest version number) available on the package manager http://ecclefechan.indigovision.com/nuget

`nuget list -AllVersions -Source "http://ecclefechan.indigovision.com/nuget"`
- lists all the nuget packages (all versions) available on the package manager http://ecclefechan.indigovision.com/nuget

`nuget sources Add -Name "IndigoVision Nuget Server" -Source http://ecclefechan.indigovision.com/nuget`
- adds a package source for the nget packages.