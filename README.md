# DevOps.Code.Entities.Metapackages.Annotations

[![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/devops-code-entities-metapackages-annotations.svg?label=AppVeyor&style=for-the-badge)](https://ci.appveyor.com/project/cdorst/devops-code-entities-metapackages-annotations)
[![NuGet package status](https://img.shields.io/nuget/v/CDorst.DevOps.Code.Entities.Metapackages.Annotations.svg?label=NuGet&style=for-the-badge)](https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.Annotations)

## Description

Metapackage for entity data-annotation attributes

## Environment Variables

This project depends on this environment variable:

Name | Description
---- | -----------
`LOCAL_NUGET_SOURCE_PATH` | *Required* to build the project, but not required during code execution. This is set to `c:\projects\nuget\cache` on the build server. On your development machine, set this to an empty, existing path. `dotnet restore` will inspect this folder prior to checking NuGet.

## Dependencies

Name | Status
---- | ------
protobuf-net | [![NuGet package status](https://img.shields.io/nuget/v/protobuf-net.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/protobuf-net)
System.ComponentModel.Annotations | [![NuGet package status](https://img.shields.io/nuget/v/System.ComponentModel.Annotations.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/System.ComponentModel.Annotations)

## Dependents

The projects below use this repository as a direct dependency.

Name | Status
---- | ------
[Addresses.States](https://github.com/CDorst/Addresses.States) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-states.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-states) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.States.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.States)
[Addresses.ZipCodes](https://github.com/CDorst/Addresses.ZipCodes) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-zipcodes.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-zipcodes) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.ZipCodes.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.ZipCodes)
[Addresses.StreetAddressLines](https://github.com/CDorst/Addresses.StreetAddressLines) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-streetaddresslines.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-streetaddresslines) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.StreetAddressLines.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.StreetAddressLines)
[Addresses.StreetAddresses](https://github.com/CDorst/Addresses.StreetAddresses) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-streetaddresses.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-streetaddresses) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.StreetAddresses.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.StreetAddresses)
[Addresses.Cities](https://github.com/CDorst/Addresses.Cities) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-cities.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-cities) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.Cities.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.Cities)
[Addresses.StateCities](https://github.com/CDorst/Addresses.StateCities) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-statecities.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-statecities) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.StateCities.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.StateCities)
[Addresses.StateCityZips](https://github.com/CDorst/Addresses.StateCityZips) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-statecityzips.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-statecityzips) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.StateCityZips.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.StateCityZips)
[Addresses.Addresses](https://github.com/CDorst/Addresses.Addresses) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/addresses-addresses.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/addresses-addresses) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Addresses.Addresses.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Addresses.Addresses)
[Entities.FooBars](https://github.com/CDorst/Entities.FooBars) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/entities-foobars.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/entities-foobars) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Entities.FooBars.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Entities.FooBars)
[Entities.StaticFooBars](https://github.com/CDorst/Entities.StaticFooBars) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/entities-staticfoobars.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/entities-staticfoobars) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Entities.StaticFooBars.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Entities.StaticFooBars)
[DevOps.Code.Entities.Metapackages.AnnotatedEntityFramework](https://github.com/CDorst/DevOps.Code.Entities.Metapackages.AnnotatedEntityFramework) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/devops-code-entities-metapackages-annotatedentityf.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/devops-code-entities-metapackages-annotatedentityf) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.DevOps.Code.Entities.Metapackages.AnnotatedEntityFramework.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.AnnotatedEntityFramework)

## NuGet


This project is published as a NuGet package at [https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.Annotations](https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.Annotations)

## Version

1.0.2

## Metaproject

DevOps.Code.Entities.Metapackages.Annotations is maintained by robots and exists because of a declarative template metaproject. View the metaproject's component directory at [https://github.com/CDorst/Project.Index](https://github.com/CDorst/Project.Index)

