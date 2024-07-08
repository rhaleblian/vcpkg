# Building OpenImageIO

    .\bootstrap-vcpkg.bat
    .\vcpkg install openimageio[tools,pybind11]:x64-windows

creates .\packages\openimageio\ .
This will include oiiotool and the Python binding.
