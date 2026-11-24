## 🔀 Open Source Contributions

**OpenVINO — Fixed a BMP buffer deallocation mismatch**

Used AddressSanitizer to reproduce the error and traced the buffer from allocation to cleanup. Replaced `delete` with `std::free()` and verified the fix with the same input.

- [Merged pull request #38735](https://github.com/openvinotoolkit/openvino/pull/38735)
- [Reproduction and verification notes](https://github.com/Jadonkim14/open-source-contributions/tree/main/openvino/pr-38735)

## ⚙️ Projects

**OpenVINO — CPU Inference Benchmark**

Implemented asynchronous inference in C using the OpenVINO C API.
Compared synchronous execution with 2, 4, and 8 asynchronous requests
over 8 runs per configuration.

Four asynchronous requests increased mean throughput by **11.90%**
(620.49 → 694.31 images/s). All **20,000 Top-10 entries** matched
the synchronous baseline for each async configuration.

## 💪 Skills

**Platforms & Languages**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![GCC](https://img.shields.io/badge/GCC-A42E2B?style=flat-square&logo=gnubash&logoColor=white)
![AddressSanitizer](https://img.shields.io/badge/AddressSanitizer-5C5C5C?style=flat-square)
