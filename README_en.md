# hk4e-patch-universal

**[English](README_en.md) | [简体中文](README.md)**

Genshin Impact encryption patch (Modded for version > 5.0)

[Click here to download the Genshin Impact server -5.3.0](https://github.com/Kei-Luna/LunaGC_5.3.0)

[Click here to download the Genshin Impact server resource package -5.3.0](https://github.com/pmagixc/5.3-res)

## Usage

### Method 1

- 1.Git repository to local
- 2.Modify the server running address and game running address in the corresponding src/modules/http.rs file based on the downloaded server running port

**Attention: The current patch specifies that the server should run on IP port 8088; The game runs on IP port 22101, and the corresponding IP port can be modified according to the port settings of the current code**

```bash
String::from("http://127.0.0.1:8088")
```

- 3.Download the Rust environment and install 'cargo', [Rust download address](https://www.rust-lang.org/tools/install)
- 4.Run start code.bat to compile the patch in the 'hk4e-patch universal' folder
- 5.Copy the compiled patch folder to the root directory of the Genshin Impact client file

### Method 2

[Click here to download patch](https://github.com/WorldDawnAres/hk4e-patch-universal/releases)

- 1.Download patch folder
- 2.Copy the patch folder to the root directory of the Genshin Impact client file

## Genshin Impact client

- Below is the download link for the full version 5.3.0

| Download link | Package size | Decompressed package size | MD5 checksum |
| --- | --- | --- | --- |
| [GenshinImpact_5.3.0.zip.001](https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20241219110745_1vT3FzXdDTDFZFrL/GenshinImpact_5.3.0.zip.001) | 10.0 GB | 20.0 GB | d7ea7d49334e03e590db3f047cd9ea88 |
| [GenshinImpact_5.3.0.zip.002](https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20241219110745_1vT3FzXdDTDFZFrL/GenshinImpact_5.3.0.zip.002) | 10.0 GB | 20.0 GB | b4178034c1d09e889e43fd76b3fb4d3c |
| [GenshinImpact_5.3.0.zip.003](https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20241219110745_1vT3FzXdDTDFZFrL/GenshinImpact_5.3.0.zip.003) | 10.0 GB | 20.0 GB | 43b70975fcb957abaaaf7d940969679a |
| [GenshinImpact_5.3.0.zip.004](https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20241219110745_1vT3FzXdDTDFZFrL/GenshinImpact_5.3.0.zip.004) | 10.0 GB | 20.0 GB | d734b1edeb1b2b0d47d4d4bab7af6778 |
| [GenshinImpact_5.3.0.zip.005](https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20241219110745_1vT3FzXdDTDFZFrL/GenshinImpact_5.3.0.zip.005) | 10.0 GB | 20.0 GB | 95abe987ff924c21f3e5085492448760 |
| [GenshinImpact_5.3.0.zip.006](https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20241219110745_1vT3FzXdDTDFZFrL/GenshinImpact_5.3.0.zip.006) | 10.0 GB | 20.0 GB | 492510ae74ae8ac696ee59b4e831d039 |
| [GenshinImpact_5.3.0.zip.007](https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20241219110745_1vT3FzXdDTDFZFrL/GenshinImpact_5.3.0.zip.007) | 10.0 GB | 20.0 GB | 0c68334b33ee878c5beac321339b9447 |
| [GenshinImpact_5.3.0.zip.008](https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20241219110745_1vT3FzXdDTDFZFrL/GenshinImpact_5.3.0.zip.008) | 0.97 GB | 1.9 GB | 18d44596a5f1467682f5e038c80bd92a |
| [Audio_Chinese_5.3.0.zip](https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20241219110745_1vT3FzXdDTDFZFrL/Audio_Chinese_5.3.0.zip) | 14.11 GB | 28.40 GB | 2727087a20d630d35efe804ae683e72e |
| [Audio_English(US)_5.3.0.zip](https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20241219110745_1vT3FzXdDTDFZFrL/Audio_English(US)_5.3.0.zip) | 16.24 GB | 32.49 GB | 76f338d1925ff39cbf73f0418e9ae354 |
| [Audio_Korean_5.3.0.zip](https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20241219110745_1vT3FzXdDTDFZFrL/Audio_Korean_5.3.0.zip) | 13.99 GB | 28.0 GB | 6356a494c7cce397bdbb1213aa6e7298 |
| [Audio_Japanese_5.3.0.zip](https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20241219110745_1vT3FzXdDTDFZFrL/Audio_Japanese_5.3.0.zip) | 18.43 GB | 36.88 GB | f2b1c1f217dafbcdf27aeece987256b7 |

- Or get the 5.2.0 -> 5.3.0 hdiffs:

| Download link | Package size | Decompressed package size | MD5 checksum |
| --- | --- | --- | --- |
| [game_5.2.0_5.3.0_hdiff_cixFUHQZyAJuOKIN.zip](https://autopatchhk.yuanshen.com/client_app/update/hk4e_global/game_5.2.0_5.3.0_hdiff_cixFUHQZyAJuOKIN.zip) | 17.16 GB | 35.14 GB | 46b32c38dbb348a172df8352074da5a1 |
| [audio_ko-kr_5.2.0_5.3.0_hdiff_oyddjWZZfxEwaTYM.zip](https://autopatchhk.yuanshen.com/client_app/update/hk4e_global/audio_ko-kr_5.2.0_5.3.0_hdiff_oyddjWZZfxEwaTYM.zip) | 0.68 GB | 1.47 GB | fcee09acf85cdd2dd1d30bdea69c9065 |
| [audio_ja-jp_5.2.0_5.3.0_hdiff_mqXJGZjryItulRRx.zip](https://autopatchhk.yuanshen.com/client_app/update/hk4e_global/audio_ja-jp_5.2.0_5.3.0_hdiff_mqXJGZjryItulRRx.zip) | 0.78 GB | 1.74 GB | 68146dc2e2ea63b0cae452ea01b23136 |
| [audio_zh-cn_5.2.0_5.3.0_hdiff_zFnGPPbohnwLAFxC.zip](https://autopatchhk.yuanshen.com/client_app/update/hk4e_global/audio_zh-cn_5.2.0_5.3.0_hdiff_zFnGPPbohnwLAFxC.zip) | 0.64 GB | 1.41 GB | 3b4f264bd791b5f81eb165fe6d36676e |
| [audio_en-us_5.2.0_5.3.0_hdiff_kFXfWOqklZrcycKa.zip](https://autopatchhk.yuanshen.com/client_app/update/hk4e_global/audio_en-us_5.2.0_5.3.0_hdiff_kFXfWOqklZrcycKa.zip) | 0.65 GB | 1.42 GB | c7189fa380b90a343cc56b7d8438eaba |
