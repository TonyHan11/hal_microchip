# Copyright (c) 2025 Microchip Technology Inc.
#
# SPDX-License-Identifier: Apache-2.0
#

add_subdirectory_ifdef(CONFIG_PIC32C  pic32c)
add_subdirectory_ifdef(CONFIG_SAM     sam)

add_subdirectory_ifdef(CONFIG_SOC_FAMILY_MICROCHIP_SAM sam)
