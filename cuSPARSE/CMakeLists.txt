# 
# Copyright (c) 2020, NVIDIA CORPORATION.  All rights reserved.
# 
# NVIDIA CORPORATION and its licensors retain all intellectual property
# and proprietary rights in and to this software, related documentation
# and any modifications thereto. Any use, reproduction, disclosure or
# distribution of this software and related documentation without an express
# license agreement from NVIDIA CORPORATION is strictly prohibited.
# 

cmake_minimum_required(VERSION 3.10.0)

project(cuSPARSESamples)

add_subdirectory(axpby)

# computecapabilty 60
#add_subdirectory(compression)

#cuSPARSELt is currently available for Linux x86-64 only and requires CUDA 11.x or newer.
#add_subdirectory(dense2sparse)
#add_subdirectory(sparse2dense)

add_subdirectory(gather)
add_subdirectory(graph_capture)
add_subdirectory(rot)
add_subdirectory(scatter)
add_subdirectory(spgemm)
add_subdirectory(spmm_coo)
add_subdirectory(spmm_csr)
#add_subdirectory(spmma)
#add_subdirectory(spmv_coo)
add_subdirectory(spmv_csr)
add_subdirectory(spvv)