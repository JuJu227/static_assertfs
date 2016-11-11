Static AssetFS 
===============

This package is complete knockoff of the [Golang sizeof tips](https://github.com/gophergala/golang-sizeof.tips) internal package which is no longer being maintain. 
---------------------------------------------------

- func Asset(name string) ([]byte, error)
  Asset loads and returns the asset for the given name. It returns an error if the asset could not be found or could not be loaded.  
- func AssetDir(name string) ([]string, error)
   AssetDir returns the file names below a certain directory embedded in the file by go-bindata. 
- func AssetFS() *assetfs.AssetFS
- func AssetInfo(name string) (os.FileInfo, error)
  AssetInfo loads and returns the asset info for the given name. It returns an error if the asset could not be found or could not be loaded.
- func AssetNames() []string
  AssetNames returns the names of the assets.

- func RestoreAsset(dir, name string) error
  Restore an asset under the given directory  
- func RestoreAssets(dir, name string) error
  Restore assets under the given directory recursively

VENDORING 
-------------
Project is using gvt, the Go vendoring tool 
[gvt](https://github.com/FiloSottile/gvt)


