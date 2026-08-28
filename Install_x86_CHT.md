# 在x86電腦上安裝Terramaster TOS 7 

# A. 準備安裝

在準備在你的DIY 電腦 ／NAS 上安裝 TOS 7之前，請準備好以下物品

1. 你的DIY 電腦，并確定能連線上互聯網 (最好在自家Router 上設定好固定IP address)，並且確定電腦的主板支援並啟用 UEFI 啟動模式。(一般新買的主機板都會支援 UEFI 啟動的。
2. 請確認你的DIY 電腦可以並已經連接 SATA 或 NVMe 介面硬碟（SATA 相容性最佳）。 不過我在 M.2  NVMe 介面硬碟上安裝也沒有問題。
3. 引導用的 USB drive [U 盤] （建議 8GB - 16GB）我自己實測2GB的也可以。
4. 到這個網址 (https://forum.terra-master.com/en/viewtopic.php?t=6433&utm_source=chatgpt.com) 下載 相關的 TOS 引導鏡像（TOS Loader .img） 到你電腦上。因為我們這次的安裝 TOS7 ，所以會使用這個  [USB Initboot Image(TOS 7 UEFI 230MB)] ⬇️ 
5. 再到官網上下載 TOS 7 安裝包（.ins 檔）官方稱為 TOS Installation Package (大約1GB左右)。你可以到官網 https://support.terra-master.com/download 找到相關文件。又或者直接點以下連結下載到你的電腦 [https://download3.terra-master.com/TOS packages/TOS installation packages/7.0/x.64/TOS_X642.0_7.0.1140_1640_2608101206.ins] ⬇️ (V 7.0.1140)
6. 準備鏡像寫入工具：如 Rufus、BalenaEtcher 或 Win32DiskImager。  這些工具很易找到，我就不提供下載連接了。

> ⭐️請注意，這裡用的都是官方的引導鏡像和安裝檔，並不需要對檔案作任何修改。
> 

# B. 開始安裝

1. 開啟 BalenaEtcher 或 Rufus。把上面第4點的 TOS 引導鏡像 寫入你的U 盤。以下為圖文教程。

先打開 BalenaEtcher ，點選 “從檔案燒錄”，然後再選擇 你電腦上的 [USB-initboot-V2037-230MB..img]，然後點選 “開啟”

![](https://raw.githubusercontent.com/TOSx86/Install-config-and-Recovery/refs/heads/main/screenshots/S1-134218.png)

然後點選 “選擇目標磁碟” ，然後選擇你的 USB drive

![](https://raw.githubusercontent.com/TOSx86/Install-config-and-Recovery/refs/heads/main/screenshots/S2-135114.png)

然後點選 “選取”

![](https://raw.githubusercontent.com/TOSx86/Install-config-and-Recovery/refs/heads/main/screenshots/S3-135539.png)
