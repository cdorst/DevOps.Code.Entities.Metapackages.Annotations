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
[Entities.FooBars](https://github.com/CDorst/Entities.FooBars) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/entities-foobars.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/entities-foobars) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Entities.FooBars.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Entities.FooBars)
[Entities.StaticFooBars](https://github.com/CDorst/Entities.StaticFooBars) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/entities-staticfoobars.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/entities-staticfoobars) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.Entities.StaticFooBars.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.Entities.StaticFooBars)

## NuGet


This project is published as a NuGet package at [https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.Annotations](https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.Annotations)

## Version

1.0.1

## Metaproject

DevOps.Code.Entities.Metapackages.Annotations is maintained by robots and exists because of a declarative template metaproject. View the metaproject's component directory at [https://github.com/CDorst/Project.Index](https://github.com/CDorst/Project.Index)

