# RotEqNet
Rotation equivariant vector field networks [[1]](#marcos2016) (to appear in ICCV 2017)

Using [MatConvNet](http://www.vlfeat.org/matconvnet) 1.0-beta25 the intallation can be done by running `vl_contrib('RotEqNet')`. For older versions it can also be unziped manually.

Run the setup script `setup_RotEqNet.m` from Matlab and then `main.m` to download the MNIST-rot dataset, train and test a rotation invariant classifier.

## Pytorch version
Anders Waldeland, from the Norwegian Computing Center, has been working on a Pytorch remake of RotEqNet! The code is available [here](https://github.com/COGMAR/RotEqNet).

<a name="marcos2016"></a>
[1] Marcos, D., Volpi, M., Komodakis, N., & Tuia, D. (2016). Rotation equivariant vector field networks. arXiv preprint arXiv:1612.09346.
