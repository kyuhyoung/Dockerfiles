# Dockerfiles

| OS           | c++    | python | cuda     | cudnn | opencv   | tensorflow | pytorch      | torchvision  | paddlepaddle   | tensorRT | tensorboard | bazel | Dockerfile and aux.files                                                                                |
| :----------: | :----: | :----: | :------: | :---: | :------: | :--------: | :----------: | :----------: | :------------: | :------: | :---------: | :---: | :------------------------------------------------------------------------------------------------------ |
| ubuntu 18.04 | 7.5.0  | 3.6.9  | 11.1     | 8.0.5 | 4.7.0.72 |            | 1.10.2+cu111 | 0.11.3+culll |                |          | 2.5.0       |       | [Dockerfile_u_18_cpp_7_5_py_3_6_cuda_11_1_cudnn_8_0_cv_4_7_torch_1_10_tv_0_11_tb_2_5](./docker_file/Dockerfile_u_18_cpp_7_5_py_3_6_cuda_11_1_cudnn_8_0_cv_4_7_torch_1_10_tv_0_11_tb_2_5) [requirements_u_18_cpp_7_5_py_3_6_cuda_11_1_cudnn_8_0_cv_4_7_torch_1_10_tv_0_11_tb_2_5.txt](./docker_file/requirements_u_18_cpp_7_5_py_3_6_cuda_11_1_cudnn_8_0_cv_4_7_torch_1_10_tv_0_11_tb_2_5.txt)                  |
| "            | "      | "      | "        | 8.0.4 | "        | 1.15.4+nv  |              |              |                | 7.2.1.4  | 1.15.999+nv | 0.24.1 | [Dockerfile_u_18_cpp_7_5_py_3_6_cuda_11_1_cudnn_8_0_cv_4_7_tf_1_15_trt_7_2_tb_1_15_bazel_0_24](./docker_file/Dockerfile_u_18_cpp_7_5_py_3_6_cuda_11_1_cudnn_8_0_cv_4_7_tf_1_15_trt_7_2_tb_1_15_bazel_0_24)               |
| "            | "      | 3.7.11 | 11.3     | 8.2.0 | 4.5.3    |            | 1.10.0       | 0.11.0       |                |          | 2.11.2      |       | [Dockerfile_u_18_cpp_7_5_py_3_7_cuda_11_3_cudnn_8_2_cv_4_5_torch_1_10_tv_0_11_tb_2_11](./docker_file/Dockerfile_u_18_cpp_7_5_py_3_7_cuda_11_3_cudnn_8_2_cv_4_5_torch_1_10_tv_0_11_tb_2_11) [requirements_u_18_cpp_7_5_py_3_7_cuda_11_3_cudnn_8_2_cv_4_5_torch_1_10_tv_0_11_tb_2_11.txt](./docker_file/requirements_u_18_cpp_7_5_py_3_7_cuda_11_3_cudnn_8_2_cv_4_5_torch_1_10_tv_0_11_tb_2_11.txt)                 |
| "            | 8.2.0  | 3.7.13 | 11.2     | 8.1.1 |          |            |              |              | 2.4.1.post1122 |          |             |       | [Dockerfile_u_18_cpp_8_2_py_3_7_cuda_11_2_cudnn_8_1_paddle_2_4](./docker_file/Dockerfile_u_18_cpp_8_2_py_3_7_cuda_11_2_cudnn_8_1_paddle_2_4)      |
| "            |        | 3.7.16 | 11.1     | 8.0.5 | 4.1.0.25 | 2.4.1      |              |              |                |          | 2.11.2      |       | [Dockerfile_u_18_py_3_7_cuda_11_1_cudnn_8_0_cv_4_1_tf_2_4_tb_2_11](./docker_file/Dockerfile_u_18_py_3_7_cuda_11_1_cudnn_8_0_cv_4_1_tf_2_4_tb_2_11) |
| ubuntu 20.04 |        |        |          |       |          |            |              |              |                |          |             |       | [Dockerfile_u_20](./docker_file/Dockerfile_u_20)                                                        |
| "            | 9.4.0  | 3.9.16 | 11.3     | 8.2.0 | 4.7.0    |            | 1.12.1+cu113 | 0.13.1+cu113 |                |          |             |       | [Dockerfile_u_20_cpp_9_4_py_3_9_cuda_11_3_cudnn_8_2_cv_4_7_torch_1_12_tv_0_13](./docker_file/Dockerfile_u_20_cpp_9_4_py_3_9_cuda_11_3_cudnn_8_2_cv_4_7_torch_1_12_tv_0_13)              |
| "            | "      | 3.9.13 | 11.3.109 | 8.2.0 | 4.7.0    |            | 2.0.0        | 0.15.1       |                |          |             |       | [Dockerfile_u_20_cpp_9_4_py_3_9_cuda_11_3_cudnn_8_2_cv_4_7_torch_2_0_tv_0_15](./docker_file/Dockerfile_u_20_cpp_9_4_py_3_9_cuda_11_3_cudnn_8_2_cv_4_7_torch_2_0_tv_0_15) [env_u_20_cpp_9_4_py_3_9_cuda_11_3_cudnn_8_2_cv_4_7_torch_2_0_tv_0_15.yaml](./docker_file/env_u_20_cpp_9_4_py_3_9_cuda_11_3_cudnn_8_2_cv_4_7_torch_2_0_tv_0_15.yaml)                 |
| ubuntu 22.04 |        |        |          |       |          |            |              |              |                |          |             |       | [Dockerfile_u_22](./docker_file/Dockerfile_u_22)                                                                    |
| "            | 11.3.0 | 3.10.6 |          |       | 4.7.0.72 |            |              |              |                |          |             |       | [Dockerfile_u_22_cpp_11_3_py_3_10_cv_4_7](./docker_file/Dockerfile_u_22_cpp_11_3_py_3_10_cv_4_7)        |
