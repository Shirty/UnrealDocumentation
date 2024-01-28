# UnrealDocumentation
Notes about Unreal

## Asset Editor and Graphs
*Currently Just Notes*

### Requirements
* a Factory and ( AssetActions ((DEPRECATED)) or AssetDefintions ( see @UAssetToolsImpl::GetNewAssetFactories() ) for your class
* The factory bCreateNew must be true or CanCreateNew should return true and the SupportedSubclass must be set
* The category can be customized see AssetDefinitions.h FAssetCategoryPath

### Editor
* see FAssetEditorToolkit ( WorkflowCentricApplication )

### What Happens?
* The system used the asset DisplayName, might want to sanitize

* likely don't need an editor necersarly, can get away with just an asset or a BT
* 
** this is discoverable though ....
