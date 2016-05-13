# Template to show Reserved properties for msbuild

	* Platform
	* MSBuildBinPath
	* MSBuildExtensionsPath
	* MSBuildExtensionsPath32
	* MSBuildExtensionsPath64
	* MSBuildLastTaskResult
	* MSBuildNodeCount
	* MSBuildProgramFiles32
	* MSBuildProjectDefaultTargets
	* MSBuildProjectDirectory
	* MSBuildProjectDirectoryNoRoot
	* MSBuildProjectExtension
	* MSBuildProjectFile
	* MSBuildProjectFullPath
	* MSBuildProjectName
	* MSBuildStartupDirectory
	* MSBuildThisFile
	* MSBuildThisFileDirectory
	* MSBuildThisFileDirectoryNoRoot
	* MSBuildThisFileExtension
	* MSBuildThisFileFullPath
	* MSBuildThisFileName
	* MSBuildToolsPath
	* MSBuildToolsVersion

## To test start bat showproperties.bat

msbuild listproperties.csproj /t:ListReservedProperties /nologo

## Result

### ListReservedProperties:

	* Configuration                   : Debug
	* Platform                        : AnyCPU
	* MSBuildBinPath                  : C:\Program Files (x86)\MSBuild\12.0\bin
	* MSBuildExtensionsPath           : C:\Program Files (x86)\MSBuild
	* MSBuildExtensionsPath32         : C:\Program Files (x86)\MSBuild
	* MSBuildExtensionsPath64         : C:\Program Files\MSBuild
	* MSBuildLastTaskResult           : true
	* MSBuildNodeCount                : 1
	* MSBuildProgramFiles32           : C:\Program Files (x86)
	* MSBuildProjectDefaultTargets    : 
	* MSBuildProjectDirectory         : C:\Projects\msbuild\Msbuild-Show-Reserved-Properties
	* MSBuildProjectDirectoryNoRoot   : Projects\msbuild\Msbuild-Show-Reserved-Properties
	* MSBuildProjectExtension         : .csproj
	* MSBuildProjectFile              : listproperties.csproj
	* MSBuildProjectFullPath          : C:\Projects\msbuild\Msbuild-Show-Reserved-Properties\listproperties.csproj
	* MSBuildProjectName              : listproperties
	* MSBuildStartupDirectory         : C:\Projects\msbuild\Msbuild-Show-Reserved-Properties
	* MSBuildThisFile                 : listproperties.csproj
	* MSBuildThisFileDirectory        : C:\Projects\msbuild\Msbuild-Show-Reserved-Properties\
	* MSBuildThisFileDirectoryNoRoot  : Projects\msbuild\Msbuild-Show-Reserved-Properties\
	* MSBuildThisFileExtension        : .csproj
	* MSBuildThisFileFullPath         : C:\Projects\msbuild\Msbuild-Show-Reserved-Properties\listproperties.csproj
	* MSBuildThisFileName             : listproperties
	* MSBuildToolsPath                : C:\Program Files (x86)\MSBuild\12.0\bin
	* MSBuildToolsVersion             : 12.0
  

