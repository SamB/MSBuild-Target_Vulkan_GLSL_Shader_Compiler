# MSBuild-Target_Vulkan_GLSL_Shader_Compiler
Thanks to this (http://reedbeta.com/blog/custom-toolchain-with-msbuild/#example-project) article I was able to put a simple buildtarget for Visual Studio and MSBuild together. 
You can just drop *.frag and *.vert files into a shader directory you'll need to create in the root of your project where the *.vcxproj is located. 
And set your projects Build Dependency to use VulkanGLSLShaderCompiler.targets. All compiled shader get the .spv extension and are placed in the same shader dir.
