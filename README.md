# WificRebirth
Patch pro dissasemblované .smali classy Wifiče, který umožňuje používání této aplikace i po jejím odepsání v roce 2017.

# Jak patchovat?
1. Stáhněte si Wifič v 1.6004 (v zahraničí se jmenuje WifiPunk). Například odtud: 

https://apkpure.com/wifipunk/com.epicqueststudios.wific/download/93-APK?from=versions%2Fversion

2. Stáhněte si xdelta: https://github.com/jmacd/xdelta-gpl/releases
3. Stáhněte libovolný .delta soubor ze stránky Releases tohoto repa.
4. V terminálu/cmd použijte: ´<název xdelta executable> -d -s <název Wifič apk souboru> <název .delta patche> <jak chcete, aby se patchnutý soubor jmenoval>´
5. Nainstalujte výsledný APK soubor do zařízení s Androidem. Vypadá to, že padá Marshmallow, ale to i některé verze origo Wifiče. Snad přijdu na to, jak to opravit.
