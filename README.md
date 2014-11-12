AIT.EF.Oracle.IdentityPatch
===========================

Oracle Databases (<12.1) do not know identity columns. Therefore the auto increment with the generated \*.edmx files does not work. This package offers a patch to change the specified columns in the project's \*.edmx files to identity columns.

## Documentation ##

See the [Wiki](https://github.com/AITGmbH/AIT.EF.Oracle.IdentityPatch/wiki) for some more documentation and an example.

## Get the Patch ##

This package is available via NuGet at https://www.nuget.org/packages/AIT.EF.Oracle.IdentityPatch

To install AIT EF Oracle Identity Patch, run the following command in the [Package Manager Console](http://docs.nuget.org/docs/start-here/using-the-package-manager-console):

    PM> Install-Package AIT.EF.Oracle.IdentityPatch

This software is provided by [AIT GmbH & Co. KG](http://www.aitgmbh.de/en/).