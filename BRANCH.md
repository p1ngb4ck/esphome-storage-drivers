# `pr/nvs`

One part of the topic repo p1ngb4ck/esphome-storage-drivers. The whole topic, with its description, is the branch `main`.

Change of this branch: `nvs`: the NVS guard - what wrote the NVS (meta record), boot check, a policy per result, protected namespaces, actions, state sensor; `preferences: nvs_backup_dir`; the `nvs` text platform

Based on these branches, whose changes it holds and builds on:

- `pr/binary-storage`: `binary_storage`: EEPROM, FRAM, MRAM and SPI flash on I2C / SPI / 1-Wire as raw or file system storages, flash partitions, LittleFS regions, NVS regions, pre-fill
- `pr/esp32-nvs-actions`: NVS browsing and erasing, API actions `nvs_list` / `nvs_erase`
- `pr/esp32-nvs-ready`: `nvs_ready`: the default NVS partition formatted when it reports no free pages or a new version
