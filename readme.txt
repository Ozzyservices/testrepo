1. About Intel® SDK for OpenCL* - CPU Only Runtime Package.

Intel® SDK for OpenCL* - CPU Only Runtime Package is an implementation of the OpenCL 1.2 standard optimized for Intel processors, running on Microsoft Windows* operating systems. 

2. Technical Requirements

Intel® SDK for OpenCL* - CPU Only Runtime Package requires support for the Intel® Streaming SIMD Extensions 4.2 (Intel® SSE 4.2) or higher (Intel Intel® Advanced Vector Extensions (Intel® AVX)). SDK works on the following CPUs, all of which contain support for the required instruction set extensions:

Mobile and Desktop Products:
- third Generation Intel® Core™ i7 Extreme Processors 
- third Generation Intel® Core™ i7 Processors
- third Generation Intel® Core™ i5 Processors
- third Generation Intel® Core™ i3 Processors
- second Generation Intel® Core™ i7 Extreme Processors 
- second Generation Intel® Core™ i7 Processors
- second Generation Intel® Core™ i5 Processors
- second Generation Intel® Core™ i3 Processors
- first Generation Intel® Core™ i7 Extreme Processors 
- first Generation Intel® Core™ i7 Processors
- first Generation Intel® Core™ i5 Processors
- first Generation Intel® Core™ i3 Processors 

Server Products:
- Intel® Xeon® Processors E7 Family
- Intel® Xeon® Processors E5 Family
- Intel® Xeon® Processors E3 Family
- Intel® Xeon® Processors, 7500, 7400, 6500 series 
- Intel® Xeon® Processors, 5500 series 
- Quad-Core Intel® Xeon® Processor 5400, 3300 series 
- Dual-Core Intel® Xeon® Processor, 5200, 3100 series

Intel® SDK for OpenCL* - CPU Only Runtime Package supports the following operating systems: 
- Microsoft Windows 7* (32-bit version)
- Microsoft Windows 7* (64-bit version)
- Microsoft Windows 7* Service Pack 1 (32-bit version)
- Microsoft Windows 7* Service Pack 1 (64-bit version) 
- Microsoft Windows Vista* Service Pack 2 (32-bit version)
- Microsoft Windows Vista* Service Pack 2 (64-bit version)
- Microsoft Windows 8* Release Preview OS 32-bit and 64-bit versions

Use Microsoft Windows 7* operating systems with Service Pack 1 to achieve better performance on 2nd Generation Intel® Core™ processors.

3. Supported features

3.1 Conformant with OpenCL 1.2 specification for the CPU, and with Microsoft Windows 7* operating systems.

3.2 Optional OpenCL 1.2 Standard Features
- Out-of-order execution model as defined in the OpenCL specification (CL_QUEUE_OUT_OF_ORDER_EXEC_MODE_ENABLE property of a command queue).
- Execution of native kernels as defined in the specification (CL_EXEC_NATIVE_KERNEL option of the CL_DEVICE_EXECUTION_CAPABILITIES property of device information).
- Image support with the minimum set of image formats, as defined in the specification (CL_DEVICE_IMAGE_SUPPORT property of device information).
- Optimization options: Intel® OpenCL SDK supports the OpenCL standard compiler flag -cl-fast-relaxed-math. Some optimizations may violate the IEEE 754 standard and the OpenCL numerical compliance. For a full list of optimized functions see Working with the cl-fast-relaxed-math Optimization Flag.
- Math intrinsic option: supports standard optional compiler flag -cl-denorms-are-zero.

3.3 OpenCL 1.2 Conformant Extensions
- cl_khr_icd - defines a simple mechanism through which the Khronos installable client driver loader (ICD Loader) may expose multiple separate vendor installable client drivers (Vendor ICDs) for OpenCL
- cl_khr_fp64 - double precision floating point support, as defined in the specification.
- cl_khr_gl_sharing - creating OpenCL context from an OpenGL* context or share group, as defined in the specification. This extension is supported on Microsoft Windows* operating systems only.
- cl_khr_gl_sharing - sharing memory objects with OpenGL* or OpenGL* ES buffers, texture and render bugger objects, as defined in the specification. 
- cl_khr_global_int32_base_atomics
- cl_khr_global_int32_extended_atomics
- cl_khr_local_int32_base_atomics
- cl_khr_local_int32_extended_atomics
- cl_khr_byte_addressable_store
- cl_khr_dx9_media_sharing
- cl_khr_d3d11_sharing

3.4 OpenCL cl_ext Extensions
- Intel Device Fission Extension Support (cl_ext_device_fission)

3.5 Intel Vendor Extensions
- Intel Immediate Command Execution Extension (cl_intel_exec_by_local_thread)
- Intel DirectX* 9 Media Sharing Extension (cl_intel_dx9_media_sharing)

For specifications of Khronos and vendor-approved OpenCL extensions please visit the Khronos OpenCL API Registry (http://www.khronos.org/registry/cl/)

Intel® SDK for OpenCL* Applications is available for downloading through Intel® Software Network (http://software.intel.com/en-us/articles/vcsource-tools-opencl-sdk/)

* OpenCL and the OpenCL logo are trademarks of Apple Inc. used by permission by Khronos.
Copyright © 2012-2013 Intel Corporation. All rights reserved.