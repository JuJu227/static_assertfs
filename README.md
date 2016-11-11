Static AssertFS 
===============

This package is complete knockoff of the [Golang sizeof tips](https://github.com/gophergala/golang-sizeof.tips) internal package which is no longer being maintain. 
---------------------------------------------------

- func Asset(name string) ([]byte, error)
- func AssetDir(name string) ([]string, error)
- func AssetFS() *assetfs.AssetFS
- func AssetInfo(name string) (os.FileInfo, error)
- func AssetNames() []string
- func RestoreAsset(dir, name string) error
- func RestoreAssets(dir, name string) error


VENDORING 
-------------
Project is using gvt, the Go vendoring tool 
[gvt](https://github.com/FiloSottile/gvt)


