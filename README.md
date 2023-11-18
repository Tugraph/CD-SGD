The body of the code comes from mxnet1.4.1

2023.11.18：
Some users have reported that it is not convenient to install our code. Now we provide another suggestion. If you have already installed mxnet and configured a distributed environment, you can directly select our following folder and file to replace the original file:

Folder1：src/kvstore/

Folder2: python/mxnet

File1:src/c_api/c_api.cc

File2:cpp-package/include/mxnet-cpp/kvstore.h

File3:include/mxnet/kvstore.h

If you have any questions about this project, you can ask and we will respond promptly and provide assistance as much as possible.