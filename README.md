# Custom Round Rainmeter Skins

1. Install [Rainmeter](https://www.rainmeter.net/)
1. Install [HWINFO](https://www.hwinfo.com/download/)
1. Install [HWINFO Rainmeter Plugin](https://www.hwinfo.com/files/RainmeterPlugin/HWiNFO_3.2.0.rmskin)
1. Copy `RoundSkin` into `$env:USERPROFILE\Documents\Rainmeter\Skins` folder

    ```Powershell
    git clone https://github.com/wlmitch/rainmeter-skins
    Set-Location rainmeter-skins
    Copy-Item -Path 'RoundSkin' -Destination "$env:USERPROFILE\Documents\Rainmeter\Skins" -Recurse -Force
    ```
1. Load RoundSkin into Rainmeter
