# sha256sum.ps1

PS Script to Compute the hash value for a file by using a specified hash algorithm and compare against origin fingerprint.


## Preface

The purpose of this PowerShell Script is to Compute the hash value for a file or an image by using a specified hash algorithm and compare against origin fingerprint. To verify the hash signature is particularly useful for downloads. An ISO image or an archive file can be checked for integrity and authenticity after downloading. For this purpose, the developers publish fingerprints with this an image for the integrity and authenticity can be compared using the SHA256 hash or MD5 hash value. So that the unchanged origin and originality can be ensured without, as might be in case of a Man-in-the-middle attack.

## Run the Script 
On a Windows workstation with PowerShell 3.0 or newer.
```
PS C:\> .\sha256sum.ps1 <image> <algorithm> <fingerprint>
```

## Parameters
Possible checksum algorithm are.
- SHA1
- SHA256
- SHA384
- SHA512
- MD5

## Feedback

If you have problems, questions, ideas or suggestions, please contact my by posting to a suitable [mail](http://think.unblog.ch/stay-in-touch)

## Git
```
git clone https://github.com/donkey/sha256sum.git
```
## Addendum

This script is intentional developed in not very structured way, so it is simply to modify individual lines or omit them altogether, it should be easily customizable.

## license

donkey/sha256sum is licensed under the GNU General Public License v3.0.
