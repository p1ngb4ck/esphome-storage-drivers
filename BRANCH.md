# `pr/binary-storage`

One part of the topic repo p1ngb4ck/esphome-storage-drivers. The whole topic, with its description, is the branch `main`.

Change of this branch: `binary_storage`: EEPROM, FRAM, MRAM and SPI flash on I2C / SPI / 1-Wire as raw or file system storages, flash partitions, LittleFS regions, NVS regions, pre-fill

Based on these branches, whose changes it holds and builds on:

- `pr/spi-nvs-pins`: `spi`: bus pins, SPI flash CS and data lines 2 / 3 read from the internal NVS
- `pr/storage` of p1ngb4ck/esphome-storage-interface: the `storage` component: registry, path / filesystem / network / raw storages, the asynchronous worker (jobs, streams), `storage.*` actions, PSRAM transfer buffer, change feed, ISO 9660 mount
