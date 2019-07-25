## Introduction

Google Chrome's DownloadMetadata file contains a lot of useful information from digital forensics and incident response perspective. DownloadMetadataParser was developed to parse DownloadMetadata. Use it as is. Testings have been done before this release. However, please feel free to reach out to me if any bugs are found.

## Version
0.5.0

## Usage
Usage: DownloadMetadataParser [DOWNLOADMETADATA_FILE]

## Example
DownloadMetadataParser DownloadMetadata

## Supported Output Format
CSV

## Supported Operating Systems
* Windows x64 (tested)
* MacOS x64 (tested)
* Ubuntu 18.04 x64 (tested)

It may work on other Linux distributions. However, testings are required to confirm them.

## SHA256
451a8461f553f7dadb039273d9db6f7f9911921d0c8fe6315b25f16940856d81  DownloadMetadataParser-0.5.0-MacOS.zip  
f7ac31827e885057b5bef174139a6119c77ca0feec2a30635b7f48e66935bfc8  DownloadMetadataParser-0.5.0-Ubuntu.zip  
0f9f82784993747aee86d8a629ae1bd574f29d0676bad80e47d13927aa671513  DownloadMetadataParser-0.5.0-Windows.zip  

## Notes
* Currently, this tool only supports UTC.

## License
Apache License 2.0
