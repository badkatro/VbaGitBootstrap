# VBA Project: VbaGitBootstrap
This cross reference list for repo (VbaGitBootstrap) was automatically created on 7/06/2017 21:49:34 by VBAGit.For more information see the [desktop liberation site](http://ramblings.mcpher.com/Home/excelquirks/drivesdk/gettinggithubready "desktop liberation")
You can see [library and dependency information here](dependencies.md)

###Below is a cross reference showing which modules and procedures reference which others
*module*|*proc*|*referenced by module*|*proc*
---|---|---|---
cJobject||vbaGit|getVGSettings
cJobject||vbaGit|getAllInfoFiles
cJobject||vbaGit|getDependencyList
cJobject||vbaGit|dependencyResolve
cJobject||vbaGit|makeCrossReferenceJob
cJobject||vbaGit|getProjects
cJobject||vbaGit|makeInfoFile
cregXLib||regXLib|rxMakeRxLib
cStringChunker||vbaGit|dependencyResolve
cStringChunker||vbaGit|makeCross
cStringChunker||vbaGit|makeReadMe
cStringChunker||vbaGit|makeDependency
cStringChunker||vbaGit|constructModLink
cStringChunker||vbaGit|makeArguments
cStringChunker||vbaGit|findModLink
cStringChunker||vbaGit|getDependencyList
cVBAArgument||cVBAProcedure|dealWithArguments
cVbaGit||vbaGit|doImportFromGit
cVbaGit||vbaGit|doGit
cVBAmodule||vbaGit|isModuleObj
cVBAmodule||vbaGit|getmoduleList
cVBAProcedure||vbaGit|getProcList
cVBAProject||vbaGit|getProjects
regXLib|rxReplace|usefulcJobject|hackJSONPObjectToJSON
regXLib|rxReplace|usefulcJobject|cleanGoogleWire
regXLib|rxReplace|usefulcJobject|hackJSObjectToJSON
urlResult|urlGet|cVbaGit|getSpecificRepo
urlResult|urlGet|cVbaGit|getFileByPath
urlResult|urlGet|cVbaGit|getUnpaged
urlResult|urlGet|cVbaGit|getMyRepos
urlResult|urlPost|cVbaGit|commitFile
urlResult|urlPost|cVbaGit|getTokenFromBasic
urlResult|urlPost|cVbaGit|createRepo
usefulcJobject|JSONParse|vbaGit|doImportFromGit
usefulcJobject|JSONParse|vbaGit|getAllInfoFiles
usefulRegex|getRx|vbaGit|dependencyResolve
usefulRegex|getTheEndRx|vbaGit|testmodulestuff
usefulStuff|Base64Encode|vbaGit|setGitClientCredentials
usefulStuff|Base64Encode|vbaGit|setGitBasicCredentials
usefulStuff|checkOrCreateFolder|vbaGit|writeInfoFile
usefulStuff|conditionalAssignment|vbaGit|modulesToInfo
usefulStuff|getAllSubFolderPaths|vbaGit|getAllInfoFiles
usefulStuff|getTimestampFromDate|vbaGit|makeInfoFile
usefulStuff|isSomething|vbaGit|getDependencyList
usefulStuff|isSomething|vbaGit|dependencyResolve
usefulStuff|isSomething|vbaGit|makeCrossReferenceJob
usefulStuff|isSomething|vbaGit|createRepos
usefulStuff|isUndefined|vbaGit|getVGSettings
usefulStuff|readFromFolderFile|vbaGit|writeTheFiles
usefulStuff|writeToFolderFile|vbaGit|writeToStagingArea
