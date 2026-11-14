# `pr/nvs`

One part of the topic repo p1ngb4ck/esphome-storage-drivers. The whole topic, with its description, is the branch `main`.

Change of this branch: `nvs`: the NVS guard - what wrote the NVS (meta record), boot check, a policy per result, protected namespaces, actions, state sensor; `preferences: nvs_backup_dir`; the `nvs` text platform

Based on these branches, whose changes it holds and builds on:

- `pr/esp32-nvs-actions`: NVS browsing and erasing, API actions `nvs_list` / `nvs_erase`
- `pr/preferences-storage`: `preferences`: flash preferences through the storage interface or an external NVS region, optional internal NVS, `keep_early`, backup / restore
