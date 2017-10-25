# CM12.1

## How launch a cm-12.1 build:
```Shell session
make clean  
repo sync  
source build/envsetup.sh  
brunch togari  
```

## How to initially set up your build tree:
```Shell session
repo init -u https://github.com/cm12-amami/android.git -b cm-12.1 
cd .repo
git clone https://github.com/colarus/local_manifests 
cd local_manifests 
git checkout cm-12.1 
cd ../.. 
repo sync
```
