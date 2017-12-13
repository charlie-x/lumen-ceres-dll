# lumen-ceres-dll
fix of the light.co ceres.dll


see here for description on how/what 

https://wordpress.com/post/charliex2.wordpress.com/1353

http://ceres-solver.org/installation.html
but since i'm using the windows version i grabbed this build,  (using submodules to get glog)

https://github.com/tbennun/ceres-windows
it needs Eigen

 http://eigen.tuxfamily.org/index.php?title=Main_Page
grabbed 3.3.4 of Eigen, extracted it to the same folder as the ceres-2015.sln file  and then renamed it to eigen

next opened the ceres-2015.sln in visual studio 2015, selected release and x64 build, built it and copied the ceres.dll to the lumen.exe folder.  after making a backup of the old non working one.
