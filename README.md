# cmake-compiler-alpine
Docker image to compile c++ cmake based projects

Prepare your compile/test script within your project and run:

docker run -v <project_folder>:/app thar/cmake-compiler-alpine ./<your_script.sh>
