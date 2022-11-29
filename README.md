# ManifoldPlus: A Robust and Scalable Watertight Manifold Surface Generation Method for Triangle Soups [**repo**](https://github.com/hjwdzh/ManifoldPlus).
输入obj带mesh的点云，输出只含表面的mesh

### Dependencies
1. Eigen
2. LibIGL

### Installing  原 prerequisites
```
git clone https://github.com/hjwdzh/ManifoldPlus.git
cd ManifoldPlus
git submodule update --init --recursive
sudo apt  install cmake
sh compile.sh

./build/manifold --input data/car_orignial.obj --output results/bathtub_manifold.obj --depth 6
```
### Installing  现 prerequisites
```
git clone 
unzip 
cd ManifoldPlus
sh compile.sh

./build/manifold --input data/car_orignial.obj --output results/bathtub_manifold.obj --depth 6
```
