# esim-tools-for-1400k-esim-whitecard
just a backup for personal usage.

EasyEUICC esim写入工具，https://easyeuicc.org/zh-hant/ 

备注：没事不要在安卓设置中禁用sim卡，不要在EasyEUICC删空esim配置，否则手机会不认卡

其余为非esim手机伪装成esim手机所需的软件，比如giffgaff等运营商申请esim时需要当前手机为esim手机，否则无法启动申请流程。
参考大神原贴：https://simonmy.com/posts/giffgaff-esim-apply-use-hookeuicc.html  


1、安装 hookEUICC esim 模块

2、安装LSPatch，注意获取应用列表的权限

3、安装euicc probe

4、伪装应用：用LSPatch给euicc probe打patch，卸载原euicc probe，重新安装打Patch后的euicc probe，可以在LSPatch中加载hookEUICC模块

5、同上述办法安装Patch后的giffgaff，在LSPatch中加载hookeuicc，即可正常申请esim


备注：Patch后的软件必须要先启动LSPatch后才能正常进入且模组生效，否则闪退。
