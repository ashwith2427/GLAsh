project('VulkanBasics', 'c','cpp',
  version : '0.1',
  default_options : ['warning_level=3','cpp_std=c++20'])
glfw=dependency('glfw3')
vulkan=dependency('vulkanheaders')
exe = executable('VulkanBasics', 'vulkanbasics.cpp',
  install : true,dependencies:[glfw,vulkan])

test('basic', exe)
