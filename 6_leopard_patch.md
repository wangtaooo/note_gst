# 6 Leopard patch


github Rep:
git@github.com:wangtaooo/Leopard.git

### 1 patch

file name:6_streaming_imx258_base28.2_CB_tx1_20190412_1.zip



6_streaming_imx258_base28.2_CB_tx1_dtbs_20190412.patch

6_streaming_imx258_base28.2_CB_tx1_kernel_20190412.patch

==============================================================
note:
mkdir ori
mv hardware ./ori/
mv kernel ./ori/

---------------------------------------------------------------
patch -p0 < 6_streaming_imx258_base28.2_CB_tx1_dtbs_****.patch
patch -p0 < 6_streaming_imc258_base28.2_CB_tx1_kernel_***.patch
---------------------------------------------------------------

mv ./ori/* .


==============================================================

Flash DTB:

sudo ./flash.sh -r -k DTB jetson-tx1 

cd Linux_for_Tegra/bootloader/signed

sudo mv tegra210-jetson-tx1-p2597-2180-a01-devkit.dtb.encrypt tegra210-jetson-tx1-p2597-2180-a01-devkit_sigheader.dtb.encrypt


sudo ./flash.sh -r -k DTB jetson-tx1 

cd Linux_for_Tegra/bootloader/signed


