# ESP32 S3 Box 3 Display for Fallout (American TV series)
## Installation
To install, add the necessary PNG lines to your `esp32-s3-box-3.yaml` file and proceed with the installation.
```yaml
---
substitutions:
  name: esp32-s3-box-3
  friendly_name: ESP32 S3 Box 3
  # Add the necessary PNG lines:
  loading_illustration_file: https://github.com/idodov/esp32-s3-box-3/raw/main/fallout/loading.png
  idle_illustration_file: https://github.com/idodov/esp32-s3-box-3/raw/main/fallout/idle.png
  listening_illustration_file: https://github.com/idodov/esp32-s3-box-3/raw/main/fallout/listening.png
  thinking_illustration_file: https://github.com/idodov/esp32-s3-box-3/raw/main/fallout/thinking.png
  replying_illustration_file: https://github.com/idodov/esp32-s3-box-3/raw/main/fallout/replying.png
  error_illustration_file: https://github.com/idodov/esp32-s3-box-3/raw/main/fallout/error.png
```

| Screen | Display |
| --- | --- |
| Idle | ![idle](https://github.com/idodov/esp32-s3-box-3/assets/19820046/8d81d5b3-0819-4188-8359-f4dc066bfdd9) |
| Error | ![error](https://github.com/idodov/esp32-s3-box-3/assets/19820046/5040c107-df09-4c8e-a5c3-2dc43544943a) |
| Loading | ![loading](https://github.com/idodov/esp32-s3-box-3/assets/19820046/8a9a5d1d-d5e7-43bc-b444-5a0c0360993d) |
| Thinking | ![thinking](https://github.com/idodov/esp32-s3-box-3/assets/19820046/7e768172-9ff3-421a-99ff-8b6bd6965fad) |
| Replying | ![replying](https://github.com/idodov/esp32-s3-box-3/assets/19820046/0556a0d7-ad36-43c9-b2fd-48e3f51c413c) |
| Listening | ![listening](https://github.com/idodov/esp32-s3-box-3/assets/19820046/2271d242-4831-4359-ad12-9944a1e3dc76) |
