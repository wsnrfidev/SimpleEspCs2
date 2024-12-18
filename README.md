# Simple Esp/Wallhack Cs2 by Csharp

# Simple Aimbot Cs2 With CSharp

[IDN]

Projek ini saya buat untuk edukasi semata tentang game hacking, disrankan untuk tidak digunakan untuk tindak kecurangan, karena bisa menyebabkan banned.
dan saya tidak bertanggung jawab apabila ada pihak tidak bertanggung jawab yang menyalahgunakan projek ini.

methode yang saya gunakan yaitu injek client.dll, dan injek cs2.exe (simple methode, tanpa bypass, jadi 99% berpotensi terkena banned).

untuk bagian ini SimpleAimbot/SimpleAimbot/Offsets.cs kalian harus selalu mengupdate masing masing offsets.
dan kalian bisa mencari offsets tersebut di https://github.com/a2x/cs2-dumper.git. di bagian output -> offsets.(language)



[ENG]

I created this project solely for education about game hacking, it is recommended not to use it for cheating, because it can result in being banned.
and I am not responsible if there are irresponsible parties who misuse this project.

The method I use is inject client.dll, and inject cs2.exe (simple method, no bypass, so 99% potential to get banned).

For this section SimpleAimbot/SimpleAimbot/Offsets.cs you must always update each offset.
and you can look for these offsets at https://github.com/a2x/cs2-dumper.git. in the output section -> offsets.(language)


[Edit this part]

Edit this // offsets -> update

int dwEntityList = 0x18C9E88;
int dwViewMatrix = 0x192B320;
int dwLocalPlayerPawn = 0x173D5A8;

// client dll -> update

int m_vOldOrigin = 0x127C;
int m_iTeamNum = 0x3CB;
int m_lifeState = 0x338;
int m_hPlayerPawn = 0x7E4;
int m_vecViewOffset = 0xC58;


