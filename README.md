# ESP32 S3 Box 3 Display for PipBoy - *FALLOUT SERIES (American TV series)*
🎦 Demo Video - https://youtube.com/shorts/XmlBikFk2Uk
## Installation
To install, add the required PNG lines to your `esp32-s3-box-3.yaml` file and proceed with the installation. Here’s an example of how to use the default images. 
> [!TIP]
> If you prefer the v2 or v3 images, simply adjust the path by adding the ‘v2’ or ‘v3’ directory.
> `.../raw/main/fallout/loading.png` --> `.../raw/main/fallout/v2/loading.png`
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

| Screen | Default | v2 | v3 |
| --- | --- | --- | --- |
| Idle | ![idle](https://github.com/idodov/esp32-s3-box-3/assets/19820046/8d81d5b3-0819-4188-8359-f4dc066bfdd9) |![idle](https://github.com/idodov/esp32-s3-box-3/assets/19820046/449cc13b-00a4-486c-907f-fdb5c8ede4c4)| ![idle](https://github.com/idodov/esp32-s3-box-3/assets/19820046/8bb61d53-b2c6-4399-aecd-31110f26998d) |
Error | ![error](https://github.com/idodov/esp32-s3-box-3/assets/19820046/5040c107-df09-4c8e-a5c3-2dc43544943a) | ![error](https://github.com/idodov/esp32-s3-box-3/assets/19820046/b60cb29a-4d88-45e9-99c0-ce6ee2607316) | ![error](https://github.com/idodov/esp32-s3-box-3/assets/19820046/c0d2afd9-1a32-476e-a9da-05c90af8dcde) |
| Loading | ![loading](https://github.com/idodov/esp32-s3-box-3/assets/19820046/8a9a5d1d-d5e7-43bc-b444-5a0c0360993d) |![loading](https://github.com/idodov/esp32-s3-box-3/assets/19820046/b7fa77c0-a162-44c5-8d9e-977b5bc300f8) | ![loading](https://github.com/idodov/esp32-s3-box-3/assets/19820046/cb1abddf-789c-496e-8706-fb2b65558eb4) |
| Thinking | ![thinking](https://github.com/idodov/esp32-s3-box-3/assets/19820046/7e768172-9ff3-421a-99ff-8b6bd6965fad) | ![thinking](https://github.com/idodov/esp32-s3-box-3/assets/19820046/1f7a2c9c-bcb1-4a9c-9cd5-0df2bbc1653c) | ![thinking](https://github.com/idodov/esp32-s3-box-3/assets/19820046/033ead49-d85a-4b42-9cf9-47446b931e12)|
| Replying | ![replying](https://github.com/idodov/esp32-s3-box-3/assets/19820046/0556a0d7-ad36-43c9-b2fd-48e3f51c413c) | ![replying](https://github.com/idodov/esp32-s3-box-3/assets/19820046/1e1a832e-779b-4d38-83ad-f587d6dbd6f0)|![replying](https://github.com/idodov/esp32-s3-box-3/assets/19820046/c5fc1ea2-f3fa-4e91-9a6e-fbc069c13542)|
| Listening | ![listening](https://github.com/idodov/esp32-s3-box-3/assets/19820046/2271d242-4831-4359-ad12-9944a1e3dc76) | ![listening](https://github.com/idodov/esp32-s3-box-3/assets/19820046/0c9255b3-a934-4361-934a-acbfa9f3b788) | ![listening](https://github.com/idodov/esp32-s3-box-3/assets/19820046/e4c087bb-0c96-4b6d-9b53-84218468f499)|
