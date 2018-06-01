FlowchainRTOS

# Introduction

[flowchain-rtos](https://github.com/flowchain/flowchain-rtos) 是一個用於 IoT Blockchain 的 FreeRTOS 特別版本（distribution），目前用於實現 Flowchain 的共識算法。

* 基於 SuperHouse 的版本，支援 ESP8266 做為 Proof-of-Concept 環境
* 使用 Open Source 的 [FreeRTOS](http://www.freertos.org) 原始碼，能研究並修改 FreeRTOS kernel 原始碼
* 使用 Open Source 的 lwip 做為 TCP/IP Stacks，能研究 FreeRTOS kernel 原始碼
* 使用 Contiki 的 CoAP (er-coap) 程式庫，支援高階 CoAP APIs

詳細的技術細節與發佈紀錄，請參考 [README_rtos-wot.md](README_rtos-wot.md)。

## License

* BSD license (as described in LICENSE) applies to original source files, [lwIP](http://lwip.wikia.com/wiki/LwIP_Wiki). lwIP is Copyright (C) Swedish Institute of Computer Science.

* FreeRTOS is provided under the GPL with the FreeRTOS linking exception, allowing non-GPL firmwares to be produced using FreeRTOS as the RTOS core. License details in files under FreeRTOS dir. FreeRTOS is Copyright (C) Real Time Engineers Ltd.

* Source & binary components from the [Espressif IOT RTOS SDK](https://github.com/espressif/esp_iot_rtos_sdk) were released under the MIT license. Source code components are relicensed here under the BSD license. The original parts are Copyright (C) Espressif Systems.

* Newlib is covered by several copyrights and licenses, as per the files in the `libc` directory.

* [mbedTLS](https://tls.mbed.org/) is provided under the Apache 2.0 license as described in the file extras/mbedtls/mbedtls/apache-2.0.txt. mbedTLS is Copyright (C) ARM Limited.

* Components under `extras/` may contain different licenses, please see those directories for details.

* CoAP as in the `coap` directory is Copyright (c) 2013, Institute for Pervasive Computing, ETH Zurich
