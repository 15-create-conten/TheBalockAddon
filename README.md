FITUR UTAMA:

1. Aktivasi altar menggunakan Nether Star.
2. Countdown sebelum ujian dimulai.
3. 3 gelombang monster dengan variasi musuh.
4. Boss utama Malgrath.
5. 3 fase pertarungan boss.
6. Pemulihan HP setiap pergantian fase.
7. Boss Bar indikator HP.
8. Efek partikel api dan lava.
9. Serangan amarah dan sambaran petir.
10. Hadiah Totem of Undying setelah menang.

KUSTOMISASI BOSS

Boss bisa diganti menggunakan Entity ID dari addon lain melalui file "main.js".

Contoh:

const boss = spawnMob(
    player,
    "minecraft:warden",
    { x: 3, y: 0, z: 0 },
    "§4MALGRATH - THE ETERNAL FURY",
    BOSS_TAG
);

Ganti "minecraft:warden" dengan Entity ID pilihan dan ubah nama boss sesuai keinginan.

KUSTOMISASI HADIAH

Hadiah kemenangan juga bisa diganti dengan item lain.

Contoh:

player.runCommand("give @s totem_of_undying 1");

Ganti "totem_of_undying" dengan Item ID pilihan.

CATATAN: Pastikan Entity ID dan Item ID valid agar addon berjalan dengan baik.
